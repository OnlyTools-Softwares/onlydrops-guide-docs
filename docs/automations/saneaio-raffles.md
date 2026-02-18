---
description: >
  This automation tool helps you submit multiple raffle entries to VegNonVeg with ease.
---

# SaneAIO Toolbox

## Installation

Download the latest version for your operating system:

- **Windows**: `SaneAIO Toolbox v3.2 [Windows].zip`
- **macOS**: `SaneAIO Toolbox v3.2 [MacOS].zip`

### Steps

1. Extract the ZIP file to a folder on your computer.
2. Run the executable:
   - **Windows**: Double-click `SaneAIO Toolbox.exe`
   - **macOS**: Double-click `SaneAIO Toolbox`  
     > You may need to allow it in **System Preferences → Security & Privacy**.

---

## Setting Up

### Authentication

On first launch, you'll need to enter your **ONLYDROPS Auth Key**.  
This is the same key you use for other OnlyDrops tools.

---

## Configuration Files

### `data/config.json`

Contains your OnlyDrops key and Discord webhook URL.

```json
{
  "ONLYDROPS_KEY": "your-key-here",
  "DISCORD_WEBHOOK": "your-webhook-url"
}
````

---

### `data/profiles/vnvprofiles.csv`

Add your VNV account credentials in CSV format:

```csv
profile_nickname,Email,Password
Profile1,email1@example.com,password123
Profile2,email2@example.com,password456
```

---

### `data/proxies.txt`

Add your proxies line by line in:

```
ip:port:user:pass
```

Example:

```
123.45.67.89:8080:username:password
98.76.54.32:8080:username:password
```

!!! tip "Managing Profiles"
Use the **Settings menu (Option 3)** to easily import or add profiles from a CSV file.
The tool will validate your profiles and create automatic backups.

---

# Using the Tool

## Main Menu

* **VNV Raffles** — Submit raffle entries
* **Toolbox** — Additional tools (Adidas order checker)
* **Settings** — Manage profiles, sessions, and configuration
* **Exit** — Close the application

---

## Running VNV Raffles

1. Select **VNV Raffles** from the main menu.
2. Enter the raffle URL when prompted.
3. Choose whether to use proxies (`y/n`).
4. Select your desired sizes (separated by `/`).
5. The tool will automatically submit entries for all your profiles.

### Example

```
[PROMPT] Enter the raffle URL: https://www.vegnonveg.com/products/shoe-name
[PROMPT] Use proxies? (y/n): y
[AVAILABLE SIZES] 7, 8, 9, 10, 11
[PROMPT] Enter the size choices (separated by /): 9/10/11
```

!!! tip "Session Persistence"
Your VNV accounts stay logged in for **30 days**.
No need to log in repeatedly — the tool automatically manages your sessions.

---

# Settings Menu

Access the **Settings** menu to:

* Replace VNV Profiles — Replace all profiles with a new CSV file
* Add VNV Profiles — Add more profiles to your existing list
* Export VNV Profiles — Save your current profiles to a file
* Clear VNV Sessions — Log out all accounts (useful if you need to refresh logins)
* Update Configuration — Change your OnlyDrops key or Discord webhook

---

# Features

* ✨ **Session Management** — Accounts stay logged in for 30 days automatically
* 🔄 **Smart Detection** — Automatically detects if you've already entered a raffle
* 📁 **Easy Profile Management** — Import, add, or replace profiles with drag & drop
* ⚡ **Fast & Reliable** — Concurrent entry submission with automatic retries
* 🔔 **Discord Notifications** — Get notified of successful and failed entries

---

# Tips

* Use proxies for better success rates and to avoid rate limiting.
* Keep your profiles CSV file backed up (automatic backups are created when importing).
* Type `back` at any prompt to return to the previous menu.
* Check the **"Already Entered"** messages to avoid duplicate submissions.

!!! warning
If you encounter any errors or issues, open a support ticket with OnlyDrops for assistance.

---

# Troubleshooting

### "License key bound to another IP"

Your IP address has changed. Reset your key in the OnlyDrops dashboard.

---

### "No profiles loaded"

Make sure your `vnvprofiles.csv` file is inside the `data/profiles/` folder and follows the correct format.

---

### "File not found" when importing

Remove any quotes or escape characters from the file path, or use drag & drop.

---

### Sessions not working

Clear all sessions from the **Settings** menu and try again.