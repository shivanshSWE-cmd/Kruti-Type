# ⚡ KrutiDev Type — Hindi Typing Speed Test Game
### कृति देव 010 टाइपिंग टेस्ट | AMOLED Theme & Remington Engine

<p align="center">
  <img src="https://img.shields.io/badge/Kruti%20Dev%20010-Remington-00E5FF?style=for-the-badge&logo=codeforces&logoColor=black" alt="Kruti Dev 010">
  <img src="https://img.shields.io/badge/Pure%20AMOLED-%23000000-00FF66?style=for-the-badge" alt="AMOLED Black">
  <img src="https://img.shields.io/badge/Zero%20Dependencies-Vanilla%20JS-FFD700?style=for-the-badge&logo=javascript&logoColor=black" alt="Vanilla JS">
  <img src="https://img.shields.io/badge/Web%20Audio%20API-Synthesizer-FF3366?style=for-the-badge" alt="Web Audio API">
  <img src="https://img.shields.io/badge/License-MIT-white?style=for-the-badge" alt="MIT License">
</p>

<p align="center">
  A high-performance, distraction-free, <b>Monkeytype-inspired Hindi Typing Speed Test</b> built specifically for the <b>Kruti Dev 010</b> font and Remington typewriter layout. Features authentic character-by-character QWERTY mapping, synthesized mechanical keyboard acoustics, 10 customizable themes, combo particle bursts, interactive Alt-code helpers, and detailed SVG performance charts.
</p>

---

## 🌟 Key Highlights

- **🎯 Authentic Remington Engine**: Matches standard Indian Government typing exams (CPCT, SSC CGL/CHSL, High Court Steno/Typist). Keystrokes map 1:1 with Kruti Dev ASCII encoding.
- **🎨 Theme & Color Studio**: 10 curated themes (AMOLED Black, Matrix Hacker, Cyberpunk Neon, Dracula, Nord Frost, Vintage Amber, Sunset Crimson, Solarized Teal, Warm Mocha, Midnight Lavender) + a custom palette builder with real-time preview and `localStorage` persistence.
- **🔊 Zero-Latency Mechanical Audio**: Synthesized via the **Web Audio API** — mechanical key click, acoustic spacebar thud, error buzz, and combo streak fanfare with zero external audio assets.
- **🔥 Gamified Streak & Combos**: Dynamic combo multiplier with HTML5 Canvas particle sparks on streak milestones (10x, 25x, 50x, 100x).
- **📊 Detailed End-Game Analytics**: Net WPM, Gross WPM, Accuracy, Consistency, and an interactive SVG chart plotting second-by-second WPM trajectories with error markers.
- **⌨️ Remington Alt-Codes & Key Map**: Comprehensive searchable Alt-codes cheat sheet (`Alt + 0216`, `Alt + 0161`, etc.) with one-click **Copy** and **Type In Test** action buttons + visual QWERTY key reference.
- **🚀 Single-File Delivery**: 100% self-contained in a single `index.html`. No `npm`, no bundlers, no build steps, and no web server required.

---

## 🎮 Game Modes

| Mode | Description | Options |
| :--- | :--- | :--- |
| **⏱️ Time Mode** | Race against the clock with live countdown | `1 min`, `5 min`, `10 min` |
| **📝 Word Mode** | Type a fixed number of words at your own pace | `25`, `50`, `100` words |
| **💀 Sudden Death** | High-stakes exam simulation | Game over on 3 strikes (❤️❤️❤️) |

---

## ⌨️ How Remington & Kruti Dev Typing Works

In legacy typing fonts like **Kruti Dev 010**, Devanagari glyphs are mapped directly to standard QWERTY ASCII keystrokes:

| QWERTY Key | Kruti Dev Glyph | Hindi Meaning | Shift Key | Shift Glyph | Hindi Meaning |
| :---: | :---: | :---: | :---: | :---: | :---: |
| `d` | `d` | **क** | `D` | `D` | **क्** (आधा क) |
| `k` | `k` | **ा** (आ की मात्रा) | `K` | `K` | **ज्ञ** |
| `j` | `j` | **र** | `J` | `J` | **श्र** |
| `e` | `e` | **म** | `E` | `E` | **म्** (आधा म) |
| `r` | `r` | **त** | `R` | `R` | **त्** (आधा त) |
| `s` | `s` | **े** (ए की मात्रा) | `S` | `S` | **ै** (ऐ की मात्रा) |
| `f` | `f` | **ि** (इ की मात्रा) | `F` | `F` | **थ्** (आधा थ) |
| `a` | `a` | **ं** (अनुस्वार) | `A` | `A` | **।** (पूर्णविराम) |

> 💡 **Tip**: Press the **⌨️ Alt Codes** button in the header or use the on-screen helper to quickly reference or auto-type complex ligatures like `Alt + 0216` (**क्र**) and `Alt + 0161` (**द्ध**).

---

## 📐 Formulas & Metrics

The typing engine calculates real-time metrics using official examination formulas:

$$\text{Gross WPM} = \frac{\text{Total Keystrokes} / 5}{\text{Time in Minutes}}$$

$$\text{Net WPM} = \max\left(0, \frac{(\text{Total Correct Keystrokes} / 5) - \text{Uncorrected Errors}}{\text{Time in Minutes}}\right)$$

$$\text{Accuracy (\%)} = \left( \frac{\text{Correct Keystrokes}}{\text{Total Keystrokes}} \right) \times 100$$

---

## ⚡ Keyboard Shortcuts

- `Tab` + `Enter` or `Esc` : Quickly restart the current test
- `Tab` : Shift focus between controls
- `Shift` + `Esc` : Close any active modal dialog

---

## 🚀 Getting Started & Deployment

### Run Locally
Since the project is completely self-contained in a single file:
1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/hindi-typing-test.git
   ```
2. Simply double-click `index.html` to open it in Google Chrome, Microsoft Edge, Firefox, or Brave.

### Deploy on GitHub Pages in 30 Seconds
1. Push this folder to your GitHub repository.
2. Go to your repository's **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, choose `Deploy from a branch`.
4. Select `main` (or `master`) branch and `/ (root)` folder, then click **Save**.
5. Your typing test is now live across the world!

---

## 📁 Project Structure

```text
hindi-typing-test/
├── index.html       # Complete application (HTML5, Embedded CSS, Audio Synthesizer, Engine & JS)
├── README.md        # Comprehensive documentation & Remington reference
├── LICENSE          # MIT License
└── .gitignore       # Standard git ignore file
```

---

## 🤝 Target Examinations & Compatibility

Ideal for candidates preparing for:
- **CPCT** (Computer Proficiency Certification Test)
- **SSC CGL / CHSL** Typing Tier
- **High Court Clerk / Steno / Typist Exams** (MP, Rajasthan, Allahabad, Patna, Delhi)
- **State Police & Secretariat Clerical Exams**
- **Railway RRB NTPC Typing Skill Test**

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) — feel free to use, modify, and distribute it for personal, commercial, or educational projects.
