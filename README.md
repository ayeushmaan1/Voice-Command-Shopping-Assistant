# 🛒 Smart Shopping Assistant

A modern, voice-controlled shopping list application that leverages browser APIs for **speech recognition** and **synthesis**.  
Built using **vanilla JavaScript, HTML5, and CSS3** — no external frameworks or backend required.

---

## ✨ Key Features

### 🎤 Voice Commands
- **Add items**: “add milk”, “add 2 apples”, “buy bread”, “get bread”, “need eggs”  
- **Remove items**: “remove milk”, “delete apples”  
- **Search products**: “find milk”, “search for bread”  
- **List management**: “clear list”, “empty list”  
- **Help**: Say “help” to see available commands  

### 🌍 Multilingual Support
- **English (US)**: “add milk”  
- **Spanish (Español)**: “añadir leche”  
- **French (Français)**: “acheter lait”  
- **German (Deutsch)**: “kaufen Milch”  
- **Hindi (हिंदी)**: “जोड़ना रोटी”  

### 🧠 Smart Functionality
- Automatic categorization (dairy, produce, grains, etc.)  
- Seasonal item suggestions  
- Substitute recommendations  
- History-based suggestions  
- Voice feedback for every action  

### 🔍 Product and Data Management
- Built-in product database (with prices & brands)  
- Voice-activated product search by name, category, or brand  
- LocalStorage persistence (saves shopping list & history in browser)  

---

## 🚀 Getting Started

### Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/voice-shopping-assistant.git
   ```
2. Open `index.html` in **Chrome** or **Edge**.  
3. Allow microphone access.  
4. Start speaking commands!  

### Live Deployment
This app is deployed as a static site on **Render**.  

🔗 **Live Demo**: [https://voice-command-shopping-assistant-pceg.onrender.com/](https://voice-command-shopping-assistant-pceg.onrender.com/)  

Render provides free HTTPS hosting, auto-deploy from GitHub, and a global CDN for fast performance.  

---

## 🛠️ Technical Overview

### Frontend Technologies
- **HTML5** – semantic and modern structure  
- **CSS3** – responsive design (Flexbox & Grid)  
- **JavaScript (ES6+)** – core app logic  
- **Web Speech API** – recognition & synthesis  
- **LocalStorage** – client-side persistence  

### Architecture
- **Voice Recognition** – handles speech-to-text  
- **NLP Parser** – regex-based command parsing  
- **Shopping List Engine** – add/remove/update items  
- **Smart Suggestions Engine** – seasonal & history-based tips  
- **Product Search** – searches mock database  
- **UI State Management** – updates list & status  

---

## 📂 Project Structure
```
voice-assistant/
├── index.html     # Main HTML file
├── styles.css     # Styling
├── script.js      # Core JavaScript logic
└── README.md      # Documentation
```

---

## 🎯 Example Commands
- “add milk” → Adds milk  
- “add 2 apples” → Adds 2 apples  
- “remove bread” → Removes bread  
- “find juice” → Searches for juice  
- “clear list” → Empties the shopping list  
- “help” → Displays help commands  

---

## 📱 Browser Compatibility
| Browser | Speech Recognition | Speech Synthesis | Status   |
|---------|--------------------|------------------|----------|
| Chrome  | ✅                  | ✅                | Full     |
| Edge    | ✅                  | ✅                | Full     |
| Firefox | ❌                  | ✅                | Partial  |
| Safari  | ❌                  | ✅                | Partial  |

💡 For best results, use **Chrome** or **Edge**.

---

## ⌨️ Keyboard Shortcuts
- **Ctrl/Cmd + M** → Start voice listening  
- **Ctrl/Cmd + S** → Focus search input  
- **Enter** → Submit search query  

---

## 🐛 Troubleshooting
- “Speech recognition not supported” → Use Chrome/Edge, ensure HTTPS  
- “Microphone access denied” → Allow mic access in browser  
- “Voice not working” → Check browser console & mic availability  
- “Items not saving” → Ensure LocalStorage is enabled  

---

## 📈 Future Enhancements
- Cloud synchronization  
- Grocery store API integration  
- Barcode scanning  
- Meal planning & recipes  
- Shared lists with family  
- Price tracking & alerts  

---

## 🤝 Contributing & License
This project is open-source under the **MIT License**.  
Contributions are welcome — fork the repo, create a branch, and submit a PR.

---

**Built with ❤️ using only native browser technologies.**
