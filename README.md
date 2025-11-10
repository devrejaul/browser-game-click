# Browser Game — Click

A lightweight browser-based **click game** built with HTML, CSS, and JavaScript. Click to earn points, trigger combos, and chase new highscores. Designed to be fast, responsive, and fun on both desktop and mobile.

## 🔗 Live Demo
- **Play now:** https://devrejaul.github.io/browser-game-click/

## ⚡ খেলার দ্রুত ধাপ
1) উপরের লিংক খুলুন  
2) টার্গেটে **ক্লিক/ট্যাপ** করুন → পয়েন্ট বাড়বে  
3) টানা দ্রুত ক্লিক করলে **combo/streak** বাড়বে → স্কোর দ্রুত বাড়ে  
4) শেষ হলে **Final Score**/ **High Score** দেখাবে (ব্রাউজারে সেভ থাকে)

## 🎮 কীভাবে খেলবেন
1) **Start/Play** বোতাম থাকলে চাপুন (না থাকলে সরাসরি টার্গেটে ক্লিক করলেই শুরু)  
2) প্রতিটি সঠিক ক্লিকে পয়েন্ট পাবেন  
3) কম সময়ে বেশি ক্লিক করলে **মাল্টিপ্লায়ার** বাড়ে (combo/streak)  
4) বেশি দেরি বা মিস হলে স্ট্রিক ভেঙে যায় → মাল্টিপ্লায়ার রিসেট  
5) স্কোর থামাতে/রিসেট করতে গেমের বোতাম ব্যবহার করুন (থাকলে)

## ⌨️ কন্ট্রোলস
- **Desktop/Laptop:** মাউস ক্লিক / ট্র্যাকপ্যাড ট্যাপ  
- **Mobile/Tablet:** স্ক্রিনে ট্যাপ  
- **Sound/FX টগল:** আইকন/সেটিংস থেকে **On/Off** (যদি থাকে)  
- **Reset/Restart:** গেম রিসেট (যদি থাকে)

## 💻 অফলাইনে চালাতে
```bash
git clone https://github.com/devrejaul/browser-game-click.git
cd browser-game-click
# Option 1: index.html ডাবল-ক্লিক করে ব্রাউজারে খুলুন
# Option 2: লোকাল সার্ভার চালান
python -m http.server 5500
# তারপর http://localhost:5500 খুলুন
```

## 🧰 Tech Stack
- HTML5
- CSS3
- JavaScript (vanilla)

## 📁 Project Structure
```
.
├── index.html
├── style.css
├── script.js
└── img/
    ├── screenshot-home.png
    └── screenshot-gameplay.png
```

## 🌐 Deploy (GitHub Pages)
1) `main` ব্র্যাঞ্চে কোড পুশ করুন  
2) Repo **Settings → Pages**  
3) Source: **Deploy from a branch** → **Branch:** `main` → **/(root)** → **Save**  
4) উপরের লাইভ লিংকে গেম চলবে

> Tip: রিলেটিভ পাথ ব্যবহার করুন: `./img/...`, `./style.css`, `./script.js`

## 🖼️ Screenshots
| Home | Gameplay |
|------|----------|
| ![Home](./img/screenshot-home.png) | ![Gameplay](./img/screenshot-gameplay.png) |

## 🗺️ Roadmap
- [ ] Power-ups & levels
- [ ] Timer / survival mode
- [ ] Sound effects & music
- [ ] Touch/gesture improvements

## 🧾 License
MIT © Rejaul Karim

## 👤 Author
**Rejaul Karim (devrejaul)**  
- GitHub: https://github.com/devrejaul  
- Live: https://devrejaul.github.io/browser-game-click/
