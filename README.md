# Trading Journal Pro V3

A clean, modern web-based trading journal to track and analyze your trading performance.

## 🚀 Live Demo

Visit: **https://faithjoydls-create.github.io/Trading-journal/**

## ✨ Features

- 📝 Log trades with entry, exit, stop loss, and take profit levels
- 📊 Track win rate and trading statistics
- 💭 Document your reasoning and lessons learned
- 🗑️ Delete individual trades
- 📱 Responsive design with dark theme
- 📲 Progressive Web App (PWA) support

## ⚙️ Setup

1. Clone the repository
2. Set up a Firebase Firestore project
3. Replace the Firebase config in `index.html`:
   ```javascript
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_AUTH_DOMAIN",
     projectId: "YOUR_PROJECT_ID"
   };
   ```
4. The site will automatically deploy to GitHub Pages!

## 📊 Track

- **Date** - Trade entry date
- **Market** - Asset/pair traded (e.g., BTC/USD, EUR/GBP)
- **Direction** - Long or Short
- **Entry/SL/TP** - Entry price, Stop Loss, Take Profit levels
- **Outcome** - Win, Loss, or Break Even
- **Reason** - Why you entered the trade
- **Lesson** - What you learned from the trade

## 🛠️ Technologies

- HTML5 + CSS3
- JavaScript (ES Modules)
- Firebase Firestore
- Progressive Web App (PWA)

## 📄 License

Public domain - feel free to use and modify!