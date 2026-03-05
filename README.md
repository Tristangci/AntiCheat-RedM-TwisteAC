<div align="center">

# 🛡️ twiste_AC - Anti-Cheat Platform for RedM 🛡️

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

### 🏃 MOVEMENT & PHYSICS
*   **Anti Noclip:** Prevents flying through walls or the ground.
*   **Anti Teleport:** Blocks instant map-wide movement and combat escapes.
*   **Anti Teleport Ped:** Stops griefers from teleporting other players.
*   **Anti Change Speed:** Blocks supernatural speed on foot, horse, or vehicle.
*   **Anti Super Jump:** Prevents unrealistic jumping over walls or obstacles.

### 🛡️ VISIBILITY & EVASION
*   **Anti Invisible:** Stops players from turning their models invisible.
*   **Anti Free Camera:** Blocks free-cam spying on roleplay scenes.
*   **Anti Spectate:** Prevents unauthorized stalking or monitoring of players.
*   **Anti Ragdoll Abuse:** Protects against forced animation/falling abuse.

### ⚔️ COMBAT & WEAPONS
*   **Anti Aim Assist:** Detects aimbots and "silent aim" for fair shootouts.
*   **Anti Blacklist Weapon:** Prevents use of explosive or admin-only guns.
*   **Anti Damage Changer:** Stops artificial weapon damage boosting (one-shots).
*   **Anti Infinity Ammo:** Blocks infinite ammo and instant magazine refills.

### 🩸 HEALTH & PROTECTION
*   **Anti Health Hack:** Prevents instant or infinite healing during fights.
*   **Anti Stamina Hack:** Blocks infinite stamina and endless sprinting.
*   **Anti God Mode:** Detects and blocks invincibility/god mode cheats.

### 👾 ENTITY & WORLD ABUSE
*   **Anti Spam (Vehicle/Ped/Object):** Prevents mass-spawning used to crash servers or cause lag.
*   **Anti Blacklist Ped:** Prohibits transforming into disruptive models (giant animals).
*   **Anti Explosion Spam:** Blocks catastrophic explosion types and continuous spam.

### 💬 CHAT & COMMUNICATION
*   **Anti Spam Chat:** Protects against flooding and repetitive harassment.
*   **Anti Blacklist Word:** Automatically filters profanity and forbidden words.
*   **Anti Play Sound:** Blocks abusive triggering of loud global sounds.

### 🔐 SYSTEM INTEGRITY
*   **Anti Inject (Lua):** Blocks external mod menus (Nightfall, RedAngel, etc.).
*   **Anti Resource Stop:** Prevents cheaters from disabling the anti-cheat.
*   **Anti Blacklist Key:** Flags keys associated with cheat menus.
*   **Anti Trigger (Blacklist/Spam):** Blocks malicious server event calls and "request flooding".
*   **Anti Economy Exploit:** Prevents injecting commands for infinite money/gold.
*   **Anti Crash:** Blocks intense visual effects/fire used to crash clients.

---

## 🖥️ WEB PANEL : PROFESSIONAL MANAGEMENT

**1. 🏠 DASHBOARD**  
Real-time overview of active alerts, online players, open cases, and sanctions. Auto-refreshing live feed.

**2. 👁️ LIVE MONITOR**  
Trigger targeted surveillance sessions. Records shots, damage, and positions in real-time with a detailed **Timeline view**.

**3. 🔔 ALERTS FEED**  
Full detection history with advanced filters by severity, status, and type. View raw evidence JSON inline.

**4. 👥 PLAYER PROFILES**  
Comprehensive history for every player, including risk scores, alert counts, and linked **Alt Accounts (Network)**.

**5. 📁 INVESTIGATION CASES**  
Organize evidence into case files with priority levels, status tracking, and team assignments.

**6. 🕵️ EXPERT REVIEW**  
*In doubt?* Request a professional analysis from our team to definitively confirm or refute cheat suspicions.

**7. ⚖️ SANCTIONS**  
Apply Warnings, Kicks, or Bans (Temp/Perm) with full audit trails and easy revocation.

**8. ⚙️ RULES ENGINE**  
Configure all detection thresholds and toggles in real-time without server restarts.

**9. 📉 STATISTICS & TRENDS**  
Visualize alert volumes, cheat types, and moderation efficiency over time.

**10. � AUDIT LOGS**  
Every staff action is recorded. Full transparency on who did what and when.

---

## �️ UNDER THE HOOD

*   **Dual Enforcement:** Hybrid detection logic running both client-side and server-side.
*   **HMAC-Signed Transport:** Secure communication between your server and our API.
*   **Async Rules Engine:** High-performance processing that doesn't impact server FPS.
*   **Multi-Tenant SaaS:** Scale your protection across multiple servers from one account.

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
* Panel login via Discord OAuth2. Your admins connect with their Discord account - no password to manage.
* Native exemptions via RedM ACE permissions: `add_ace identifier.steam:xxx anticheat.exempt allow`

---

## 💡 DESIGN PHILOSOPHY

* **"Evidence before sanctions"** → Every flag is documented and reviewable
* **"Observe before you enforce"** → Safe default mode, no risk to start
* **"Multi-signal correlation"** → No ban on a single isolated indicator
* **"Full reversibility"** → Every sanction can be lifted

---

<div align="center">

**twiste_AC - Built for serious servers. Deploy with confidence.**

🌐 Visit us at: [https://panel.twiste-services.net](https://panel.twiste-services.net)
**RedM Protection | RedM Anti-Cheat | Web Dashboard**

</div>
