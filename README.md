# SecurePassCheck

Modern, client-side password security toolkit.  
Privacy-first • Zero-knowledge • Local-only • No server involved

**Analyze password strength • Encrypt & store securely • Monitor your security posture — all in your browser.**

Current version: **2026 edition** (static HTML + Tailwind + vanilla JS)

## ✨ Features

- **Home / Landing page**  
  Clean introduction with animated typing effect and quick-access cards

- **Password Strength Analyzer**  
  Real-time feedback  
  Entropy bits calculation  
  Approximate crack-time estimation  
  Common password / leaked password detection  
  Detailed criteria checklist  
  Radar chart visualization of composition  
  Suggested stronger variants

- **Encryption Vault**  
  Local encryption/decryption with:  
  • AES-256 (CryptoJS)  
  • Base64 encoding  
  • Simple symmetric XOR (for demonstration)  
  Optional custom key or auto-generated  
  History log with timestamps, method, length  
  Search, delete, quick re-decrypt buttons  
  Copy-to-clipboard support

- **Security Dashboard**  
  Total passwords • Strong passwords count  
  Average strength percentage  
  Overall security score (0–100)  
  Progress bar with color zones  
  Strength distribution pie chart  
  7-day vault activity bar chart  
  Personalized security recommendations  
  Quick actions (analyze, add to vault, export, report)

## 🛠️ Tech Stack

- HTML5 + CSS  
- Tailwind CSS (via CDN)  
- Vanilla JavaScript  
- [ECharts](https://echarts.apache.org/) v5 — charts  
- [CryptoJS](https://github.com/brix/crypto-js) v4 — AES & Base64  
- Google Fonts: Inter + Roboto Mono  
- Browser storage: `localStorage` for vault history

**No build tools • No frameworks • No backend • Works offline**

## 📂 Project Structure


## 🚀 How to Use

1. Download or clone the repository
2. Open **any** `.html` file in a modern browser  
   (Chrome, Edge, Firefox, Safari — latest versions recommended)
3. Start using:

   - Analyze passwords on **strength.html**  
   - Encrypt & store them on **vault.html**  
   - View your overall posture on **dashboard.html**

> All your data stays in **your browser only** (`localStorage`).  
> Clearing browsing data / using private mode will delete your vault entries.

## 🔐 Security & Privacy Notes

- **No network requests** — nothing is sent to any server
- AES-256 encryption happens entirely client-side (CryptoJS)
- Vault history is stored **unencrypted** in `localStorage`  
  → This project is **educational / personal-use oriented**  
  → For serious long-term storage, use a dedicated password manager
- Not security audited — treat as a learning / demo project

## 🎯 Planned / Possible Future Enhancements

- Master password to protect vault entries
- Encrypted vault export / import (.json)
- Integrated strong password generator
- Optional "Have I Been Pwned?" check (with user consent)
- Theme switcher (dark/light)
- Notes / category / favorite flags for vault items
- Better mobile experience (touch-friendly inputs)

## 📄 License

MIT License

You are free to use, modify, fork, learn from, and share this project.

## ❤️ Credits & Thanks

Built with passion in Kurunegala, Sri Lanka  
© 2026 Kawya

Enjoy safer passwords!
