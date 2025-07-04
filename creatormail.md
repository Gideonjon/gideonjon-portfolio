# CreatorMail — Send Onchain Emails with Wallet Addresses

**📦 Type:** Personal Project  
**🎯 Role:** Fullstack Builder  
**🧠 Stack:** Vue.js, Firebase, EmailJS, ENS/CreatorID Integration, Flutter  
**🌐 Live:** [creatormail.vercel.app](https://creatormail.vercel.app)  
**💡 Ecosystem:** Creator Chain (Base-compatible)

---

## 📫 What It Does

CreatorMail is a lightweight web tool that lets anyone send emails to **wallet addresses** or **Creator usernames** — even without knowing their actual email.

### Use Cases:
- Announcements to DAO contributors
- Airdrop notifications
- Sending email receipts after onchain events

---

## 🛠 Features I Built

- Users can send emails to any:
  - Ethereum address
  - ENS or `*.creator` username
- Behind the scenes, I resolve wallet → email via Firebase database mapping.
- Messages are sent securely using **EmailJS** with user-input form.
- Added validation for valid address/username formats
- Designed mobile-responsive Vue.js UI with simple animations and status feedback

---

## 💡 Highlights

- No login required — just send & go
- Lightweight and fast; deploys under 2 seconds on Vercel
- Can be integrated into other dApps via URL query params (e.g., `?to=0x123...`)

---

## 🧠 Future Ideas

- Add wallet-based auth to protect senders
- Encrypt messages using Lit Protocol or similar
- Auto-resolve emails using Creator Chain profiles
- Build a webhook API to send programmatically

---

## 🔗 Live Project

👉 [creatormail.vercel.app](https://creatormail.vercel.app)

---

## 💬 Want to add this tool to your Creator-based app?

I'm available for Creator ecosystem tools, web3 messaging dApps, or Firebase + Web3 integrations.

📩 Email me: [gideonjopnes63@gmail.com]  
🐦 Twitter: [https://twitter.com/yourhandle](https://twitter.com/codewithananam)
