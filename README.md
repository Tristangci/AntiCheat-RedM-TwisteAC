<div align="center">

# 🛡️ twiste_AC — Anti-Cheat Platform for RedM 🛡️

**Surveillance, detection and enforcement system for RedM servers**
**All-in-one package: Lua Resource + Professional Web Panel**

🌍 **Official Website:** [Twiste Services - RedM Access Security](https://panel.twiste-services.net)

</div>

---

## 🚀 WHAT YOU GET

📦 **REDM RESOURCE (`twiste_AC`)**
* Real-time detection running directly on your server
* Simple configuration via `server.cfg` convars & Panel setup
* "Observe only" mode to start safely, zero risk

🖥️ **WEB ADMINISTRATION PANEL (twisteAC Dashboard)**
* Full interface accessible from your browser
* Secured login via Discord OAuth2
* 10 operational modules detailed below

---

## 🔍 DETECTION : WHAT IS MONITORED IN-GAME

* **MOVEMENT & POSITION**: Abnormal speed, instant teleportation, noclip detection. Adaptive thresholds: on foot / horse / vehicle / swimming.
* **COMBAT & WEAPONS**: Headshot rate tracking on a sliding window, silent aim detection. Shot ↔ impact correlation to identify aimbot patterns. Impossible damage based on range and weapon type.
* **HEALTH & GODMODE**: Hook on direct health modification attempts. Active invincibility flag monitoring. Regeneration speed analysis.
* **ECONOMY (VORP & Custom)**: Transaction tracking for money and inventory. Item duplication and money injection detection.
* **CHEAT MENUS**: Key combination detection associated with known cheat menus. Behavioral analysis after suspicious key press (sudden freeze, etc.).
* **CLIENT INTEGRITY**: Cryptographic heartbeat (verifies client is unmodified). Detection of unauthorized resources loaded client-side.
* **SUSPICIOUS ENTITIES**: Scan of entities attached to the player ped. Automatic cleanup if threshold is exceeded.

---

## 🖥️ WEB PANEL : 10 OPERATIONAL MODULES

**1. 🏠 DASHBOARD**
Real-time overview: active alerts, online players, open cases, active sanctions. Live feed of the 5 latest alerts. Auto-refresh every 30 seconds.

**2. 👁️ SURVEILLANCE**
Manually trigger or stop targeted surveillance on any player. Lists active sessions and history. Each session records shots, damage events, and positions in real time.
*→ Detailed Timeline view per session*

**3. 🔔 ALERTS**
Full detection feed. Filter by severity (CRITICAL / HIGH / MEDIUM / LOW), by status (New / Investigating / Resolved / False Positive), and by type (Teleport, Speed, Headshot, Duplication...). Actions: Investigate, Resolve, Flag as FP. Evidence JSON data shown inline per alert.

**4. 👥 PLAYERS**
Full list of all known players. Filters: Online / Flagged / Banned. Per player: risk score (0-100%), alert count, sanction count, first/last seen dates. Visual badge if the player is currently under active surveillance.
*→ Detailed profile with full player history*

**5. 📁 CASES (INVESTIGATIONS) & 🕵️ EXPERT REVIEW**
Create investigation folders linked to a player. Each case has a title, description, status (Open / Investigating / Resolved / Closed), priority (LOW → CRITICAL), and an assignee. Integrated player search. *→ Detailed view with action log.*
✨ **NEW FEATURE: EXPERT REVIEW** ✨
*In doubt about a player? Request a professional expert review directly from their Case file. Our anti-cheat expert team will analyze the evidence, logs, and videos to definitively confirm or refute the cheat verification.*

**6. ⚖️ SANCTIONS**
Apply punishments: Warning / Kick / Ban. Configurable duration (temporary or permanent). Real-time remaining time display. Manual revocation possible at any time.
*→ Detailed view with comment support*

**7. ⚙️ RULES**
Configure detection rules without restarting the server. Each rule has a category, severity, enabled/disabled toggle, and advanced configuration parameters.

**8. 🖧 SERVERS**
Register and manage your RedM servers. View status, API key, and activity per server.

**9. 📊 STATISTICS**
Trend charts: alert volume over time, breakdown by cheat type, resolution rate. Exportable data for your moderation reports.

**10. 🏥 METRICS & HEALTH**
Live connection indicator in the sidebar (green/red dot). API availability monitoring. System health data.

---

## ⚙️ CONFIGURATION (RedM Server Side)

Add these lines to your `server.cfg`:

```cfg
setr ac_api_key "PROVIDED_API_KEY"
ensure twiste_AC
```

→ All thresholds are adjustable from the web panel, no restart required.

---

## 🔐 SECURITY

* All decisions are made server-side. The client cannot manipulate the system on its own.
* Every action is logged and timestamped. Any sanction can be revoked in one click with a full audit trail retained.
* Panel login via Discord OAuth2. Your admins connect with their Discord account — no password to manage.
* Native exemptions via RedM ACE permissions: `add_ace identifier.steam:xxx anticheat.exempt allow`

---

## 💡 DESIGN PHILOSOPHY

* **"Evidence before sanctions"** → Every flag is documented and reviewable
* **"Observe before you enforce"** → Safe default mode, no risk to start
* **"Multi-signal correlation"** → No ban on a single isolated indicator
* **"Full reversibility"** → Every sanction can be lifted

---

<div align="center">

**twiste_AC — Built for serious servers. Deploy with confidence.**

🌐 Visit us at: [https://panel.twiste-services.net](https://panel.twiste-services.net)
**RedM Protection | RedM Anti-Cheat | Web Dashboard**

</div>
