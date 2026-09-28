# 🧠 APTI DUDE

> **Think sharper. Solve deeper.**
>
> A premium, browser-native IQ & aptitude intelligence platform. Zero dependencies. Pure intelligence.

---

## ✨ What is APTI DUDE?

APTI DUDE is a **single-page, fully-interactive** practice platform for sharpening aptitude, reasoning, and IQ skills. Built entirely in HTML, CSS, and JavaScript—no build tools, no backend, no friction. Open `index.html` and start training.

### Designed for:
- **Job seekers** prepping for company aptitude assessments (TCS, Infosys, etc.)
- **Students** building speed and accuracy across reasoning domains
- **Competitive exam takers** tracking progress and skill evolution
- **Self-learners** who value clean UX and frictionless practice

---

## 🎯 Core Features

| Feature | Details |
|---------|---------|
| **📊 Progressive Levels** | Beginner → Advanced → Pro Master → IQ Master |
| **⏱️ Timed Assessments** | Real-time scoring, question navigation, instant feedback |
| **📚 8 Skill Domains** | Quantitative, Logical, Verbal, Analytical, Technical, Math, Data, IQ |
| **🏢 Company Practice** | TCS, Infosys, and more—labeled practice families |
| **💾 Persistent Progress** | Browser localStorage keeps your dashboard state alive |
| **🎨 Premium Design** | White, sandal, and gold UI with animated particles |
| **📱 Fully Responsive** | Desktop and mobile optimized |
| **⌨️ Terminal Console** | Built-in progress tracker and command interface |

---

## 🚀 Quick Start

### Option 1: Direct Browser (Fastest)
```bash
git clone https://github.com/saravanavel07/APTIDUDE.git
cd APTIDUDE
# Open index.html in your browser
```

### Option 2: Local Server
```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server
```
Then visit: `http://localhost:8000`

### Option 3: GitHub Pages
Push to GitHub, enable Pages from repo settings (main branch, root folder), and your app deploys instantly.

---

## 📖 How It Works

1. **Pick a domain** – Choose from Quantitative, Logical, Verbal, Analytical, Technical, Math, Data Interpretation, or IQ Master
2. **Select difficulty** – Or browse company-specific practice families
3. **Answer questions** – Timed quiz mode with instant navigation and scoring
4. **Track progress** – Your results, points, streak, and level appear on your personal dashboard
5. **Build mastery** – Repeat, improve, unlock higher levels

**All progress is stored locally in your browser.** No account, no cloud, no tracking.

---

## 📊 Skill Dimensions

- **Quantitative Aptitude** – Percentages, ratios, averages, profit & loss, time, work, algebra
- **Logical Reasoning** – Series, coding-decoding, syllogisms, puzzles, directions, deductions
- **Verbal Ability** – Vocabulary, grammar, sentence correction, comprehension, verbal logic
- **Analytical Reasoning** – Charts, tables, patterns, comparisons, case analysis
- **Mathematics** – Arithmetic, algebra, geometry, statistics, sequences
- **Data Interpretation** – Tables, graphs, ratios, trends, quantitative comparisons
- **Technical Practice** – Programming logic, DSA, SQL, databases, OOP
- **IQ Master** – Pattern recognition, deduction, sequences, spatial reasoning

---

## 🏗️ Project Structure

```
APTIDUDE/
├── index.html          # Full app (HTML + CSS + JS, ~28KB)
├── README.md           # Documentation
├── LICENSE             # MIT
└── [No build files, dependencies, or config needed]
```

**That's it.** One file. One open command. One browser tab.

---

## 💡 Tech Stack

| Layer | Technology |
|-------|-----------|
| **Markup** | HTML5 |
| **Styling** | CSS3 (Grid, Flexbox, Animations) |
| **Logic** | Vanilla JavaScript |
| **Storage** | Browser localStorage |
| **Fonts** | Google Fonts (DM Sans, Playfair Display) |
| **Build** | None required |

---

## 🎨 Design Highlights

- **Premium warm palette** – Cream, sand, gold, ink on white
- **Animated particles** – Mathematical symbols float subtly in the background
- **Glass morphism** – Blurred navigation, layered cards
- **Dark mode UI** – Terminal console for accessibility
- **No external assets** – All inline CSS and JS
- **Smooth interactions** – Subtle transitions and hover effects

---

## ⚙️ How Questions Work

The app includes a curated **question bank** covering all 8 domains and 4 difficulty levels:

```javascript
{
  t: "Quantitative Aptitude",
  d: "Beginner",
  q: "If 20% of a number is 50, what is the number?",
  o: ["200", "250", "300", "350"],
  a: 1  // Answer index
}
```

Questions are **shuffled on each quiz**, and your answers are stored in the quiz session for scoring.

---

## 📈 Progress Tracking

Your dashboard tracks:
- **Tests completed** – Total quiz runs
- **Questions answered** – Cumulative answer count
- **Best score** – Highest percentage achieved
- **Current streak** – Consecutive correct answers
- **Master points** – Accumulating progress toward next level
- **Current level** – Your achievement tier

All stored in `localStorage` under the key `aptiDudeState`.

---

## 🔒 Privacy & Disclaimer

- **No external tracking.** All data stays in your browser.
- **Company names** are used as practice-category labels only. APTI DUDE does not reproduce or represent official hiring assessments from any organization.
- **Clearing browser storage** will reset your progress. Consider exporting your stats first.

---

## 📦 Deployment

### GitHub Pages (Recommended)
1. Push this repo to GitHub
2. Go to **Settings** → **Pages**
3. Select **main** branch, **root** folder
4. Save
5. Your site is live at `https://<username>.github.io/APTIDUDE`

### Alternatives
- Netlify (drag-and-drop deployment)
- Vercel (zero-config)
- Any static host (AWS S3, Cloudflare Pages, etc.)

---

## 🛠️ Customization

Want to extend APTI DUDE?

- **Add more questions** – Edit the `bank` array in `index.html`
- **Adjust styling** – Modify CSS variables in `:root`
- **Change UI text** – Search and replace brand/section titles
- **Add new topics** – Insert new category objects into the question bank

All within a single `index.html` file.

---

## 📝 License

MIT License – Use, modify, and distribute freely. See [LICENSE](LICENSE) for details.

---

## 🎯 Vision

APTI DUDE exists because aptitude training should be:
- ✅ **Immediate** – No installation, no signup, no delays
- ✅ **Private** – Your progress is your own
- ✅ **Beautiful** – Design that motivates practice
- ✅ **Focused** – No distractions, just learning
- ✅ **Accessible** – Works on any device with a browser

**Train the brain. Master the challenge.**

---

**Made with ❤️ by [saravanavel07](https://github.com/saravanavel07)**

[🚀 Start Practicing](https://github.com/saravanavel07/APTIDUDE/blob/main/index.html)
