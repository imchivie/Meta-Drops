# Meta Drops - Automated Twitch Drops Tool

![Banner](https://i.imgur.com/yHwlXRl.png)

## 📌 Overview

Automatically checks Twitch streams for active drops and manages browser sessions to farm rewards.

## ✨ Features

- ✔️ Checks multiple Twitch streams for live status
- ✔️ Automatically opens streams with browser
- ✔️ Countdown timer with visual feedback
- ✔️ Logs completed/skipped streams
- ✔️ Configurable browser selection

## 🛠️ Installation
1. Download the latest release
2. Place executable in desired folder
3. Run `MetaDrops.exe`
4. Edit `MetaDrops_Data/Links.txt` with Twitch URLs

**Data folder will be created automatically after you run `MetaDrops.exe`**


## ⚙️ Configuration

Edit these files in `MetaDrops_Data` folder:

- `Links.txt` - Add Twitch stream URLs (one per line)
- `Config.txt` - Set preferred browser (brave/chrome/firefox/edge)

## 📂 File Structure

MetaDrops/
- ├── MetaDrops.exe
- └── MetaDrops_Data/
  -   ├── Links.txt # Stream URLs
  -   ├── Config.txt # Browser settings
  -   ├── Done.txt # Completed streams log
  -   ├── Skipped.txt # Skipped streams log
  -   └── Errors.log # Error records

## 🚀 Usage

1. Launch application
2. Enter watch duration (minutes)
3. Tool will:
  - Check all streams
  - Open live ones in browser
  - Track viewing time
  - Log results

## 📜 License

MIT License - See [LICENSE](LICENSE) file

---

🔧 **Maintainer**: [@cjchivie](https://github.com/imchivie)  
🐛 **Report Issues**: [Issue Tracker](https://github.com/imchivie/Meta-Drops/issues) _[@cjchivie](https://github.com/imchivie/Meta-Drops/issues)_
