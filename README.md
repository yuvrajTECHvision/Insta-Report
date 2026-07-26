# ⚡ InstaReporter V2

<p align="center">
  <img src="https://shields.io" alt="Python">
  <img src="https://shields.io" alt="Premium Release">
  <img src="https://shields.io" alt="Maintained">
  <img src="https://shields.io" alt="Platforms">
</p>

An advanced, asynchronous multi-account automated automation engine designed to submit structured reports on Instagram profiles and posts. Equipped with dynamic security bypassing, intelligent proxy rotation, and smart HTML fallback parsers to completely bypass standard scraper mitigation systems.

Developed with a sleek, neon hacker-style command-line interface tracking comprehensive real-time execution states.

---

## 🔒 Access & Licensing Notice

> [!WARNING]
> **This tool is not open-source.** Standard `git clone` or direct usage is unavailable. The runtime files are encrypted/secured. You must contact the developer directly to purchase the access password for the software package.

### 🔑 Critical Prerequisites
* **File Password Required:** Accessible only via direct purchase from the creator.
* **Authentication Enforced:** You **must provide a valid Instagram Session ID (`sessionid`)** inside the configuration file for the engine to operate. Anonymous or unauthenticated requests are discarded automatically by the platform's security layers.

---

## ✨ Core Features

- **⚡ Blazing Fast Performance:** Powered entirely by `asyncio` and `aiohttp` for non-blocking concurrent request tracking loops.
- **🛡️ Rate-Limit Avoidance:** Smart proxy handling featuring random cooldown delays and automatic bad-node elimination.
- **🔄 Multi-Account Mass Loops:** Seamlessly cycles through an unlimited pool of session cookies distributed evenly across targets.
- **🔮 Smart HTML Fallback Parsing:** Custom Regular Expression metadata scrapers that extract Numerical IDs even when backend JSON endpoints are blocked.
- **🌐 Dual Proxy Acquisition:** Natively supports both dynamic live public scraping APIs and private credential-authenticated proxy files.
- **🎨 Stylish Visual Terminal Layout:** Premium Neon CLI environment equipped with automatic window clearing and real-time execution timestamps.

---

## 🎨 Preview Layout

```text
    .___           __        __________                               __                 

    |   |  ____   /  |_ ____ \______   \ ____ ______   ___________  _/  |_  ___________  
    |   | /    \  \   __\__  \ |       _// __ \\____ \ /  _ \_  __ \ \   __\_/ __ \_  __ \ 
    |   ||   |  \  |  |  / __ \|    |   \  ___/|  |_> >  <_> )  | \/  |  |  \  ___/|  | \/ 
    |___||___|  /  |__| (____  /____|_  /\___  >   __/ \____/|__|     |__|   \___  >__|    
              \/             \/       \/     \/|__|                              \/        

  ┌────────────────────────────────────────────────────────────────────────┐
  │ CORE ENGINE: v2.4.0 │ MADE BY: Yuvraj │ DISCORD: yuvieg │ BUILD: STABLE │
  └────────────────────────────────────────────────────────────────────────┘

[12:28:14] [⚙] Resolving User ID for: target_username
[12:28:15] [*] JSON endpoint restricted. Fetching public web layout source...
[12:28:16] [+] Found Numerical ID via HTML fallback parsing: 76745130716
[12:28:16] [⚙] Submitting payload against Resolved ID: 76745130716
[12:28:17] [✔] Successfully sent report tracking state for: target_username
```

---

## 🚀 Installation & Configuration

1. **Acquire the Secured Files:** Download the release distribution package from the official source channel.
2. **Unlock the Archive:** Enter your purchased premium authorization password when extracting the directory contents.
3. **Install Dependencies:** Run our single-line utility command in your command-line environment:
   ```bash
   pip install "requests>=2.31.0" "colorama>=0.4.6" "pyfiglet>=0.8.post1" "termcolor>=2.3.0" "python-dotenv>=1.0.0" "aiohttp>=3.8.6" "asyncio>=3.4.3" "tqdm>=4.66.1" pyyaml aiofiles
   ```
4. **Configure Your Credentials:**
   Open the `config.yml` file and update your proxy lists and account session pool:
   ```yaml
   proxy_file: proxies.txt
   max_retries: 3
   timeout: 10
   user_agent_rotation: true
   # Paste all your active session IDs inside square brackets below
   session_ids: ["sessionid_value_1", "sessionid_value_2"]
   ```
5. **Launch the Engine:**
   ```bash
   python ir.py
   ```

---

## ⚙️ How to Extract Your Session ID

1. Open your computer's browser and log into [Instagram](https://instagram.com).
2. Press **F12** to open the developer dashboard tools.
3. Head to the **Application** or **Storage** tab, choose **Cookies**, then select `https://instagram.com`.
4. Locate the row named **`sessionid`**, double-click its value, and copy the entire string into your `config.yml` file.

---

## 👤 Developer Contact & Sales

To buy the password key or ask questions about the project, contact the lead core architect directly:

* **Developer:** Yuvraj
* **Discord Username:** `yuvieg`
* **GitHub Repository:** [yuvrajTECHvision/Insta-Report](https://github.com)

---

## ⚖️ Disclaimer

This utility is developed purely for educational, testing, and security analysis contexts. The developer holds zero legal liability or responsibility for potential accounts banned, network locks, or misuse of this codebase violating corporate platforms Terms of Service structures.
