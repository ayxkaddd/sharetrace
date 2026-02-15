<h1 align="center">ShareTrace</h1>
<p align="center">🎭 Reveal the identity behind a share link</p>
<p align="center">
  <img src="assets/capture.png" />
</p>

---

> ⚠️ **Archive Notice**  
> This repository is an **archive of the deleted `loaded/sharetrace` project**.  
> **I am not the author of the original code.** It is preserved here for reference and educational purposes only.

---

## 💻 Quick Start

```bash
python -m sharetrace <url>
```

## 📚 Advanced usage:
```bash
# Output as JSON for piping
python -m sharetrace <url> --json

# List all supported platforms
python -m sharetrace --list
```

## ⚙️ Installation

```bash
git clone https://github.com/loaded/sharetrace.git
cd sharetrace
pip install -r requirements.txt
```

## Supported sources

| Name                | Extracts |
| ------------------- | -------- |
| [TikTok](https://tiktok.com)              | User ID, Username, Display Name, Country, Device, Timestamp |
| [Instagram](https://instagram.com)        | Username, Display Name, User ID, Profile Pic |
| [Discord](https://discord.com)            | User ID, Username, Display Name, Avatar, Creation Time |
| [ChatGPT](https://chatgpt.com)            | Display Name |
| [Perplexity](https://perplexity.ai)       | Username, Avatar, User ID |
| [Microsoft](https://sharepoint.com)       | Email (From SharePoint/OneDrive links) |
| [Pinterest](https://pinterest.com)        | Username, User ID, Display Name, Avatar |
| [Substack](https://substack.com)          | User ID, Name, Handle, Bio |
| [Suno](https://suno.com)                  | Username, Display Name, Avatar |
| [Telegram](https://telegram.org)          | User ID (From joinchat links) |

## 😊 SOWEL classification
This tool uses the following OSINT techniques:
- [SOTL-1.4. Analyze Internal Identifiers](https://sowel.soxoj.com/internal-identifiers)
- [SOTL-3.1. Extract Metadata From User-Generated Content](https://sowel.soxoj.com/Techniques/SOTL-3.1.+Extract+Metadata+From+User-Generated+Content)

## ⚠️ Ethical Use & Disclaimer

This tool is created for **educational and defensive purposes only**.
- Only analyze links that have been publicly shared or sent to you.
- I am not responsible for any misuse of this tool.