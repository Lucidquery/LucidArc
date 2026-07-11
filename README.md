# LucidArc

<div align="center">

**The AI-Powered Command Bar for Windows**

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?logo=windows&logoColor=white)](https://lucidquery.com/lucidarc/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.2%20Alpha-EC4899)](https://lucidquery.com/lucidarc/)
[![Built with Go](https://img.shields.io/badge/Built%20with-Go-00ADD8?logo=go&logoColor=white)](https://golang.org/)

Ultra-fast Windows command bar with AI integration. Search files instantly, convert currencies/units, calculate expressions, manage clipboard history, and access AI for translation, code generation & web browsing.

[Download](https://lucidquery.com/lucidarc/) • [Features](#features) • [Getting Started](#getting-started)

</div>

<p align="center">
  <img src="assets/lucidarc-presentation.png?v=2" alt="LucidArc Presentation" width="800">
</p>

---

## What is LucidArc?

LucidArc is a blazingly fast command bar for Windows that transforms how you interact with your computer. Think Raycast or Spotlight, but built specifically for Windows with deep AI integration and unparalleled performance.

**Built in Go** for maximum speed and efficiency, LucidArc is lightweight (<50MB), keyboard-driven, and designed for power users who value productivity and workflow optimization.

### Why LucidArc?

- **Lightning Fast:** Built in Go, optimized for speed. Launch apps and find files in milliseconds.
- **AI-Powered:** Integrated AI assistant for translation, code generation, web browsing, and content transformation.
- **Keyboard-First:** Never touch your mouse. Everything accessible via keyboard shortcuts.
- **Intelligent Clipboard:** Never lose what you copy. Searchable history with AI transformations.
- **No Sign-Up Required:** Download and start using immediately. No account creation necessary.
- **Free & Open Source:** Core features available at no cost, forever.

---

## Features

### 🔍 **Instant File Search**
Find any file on your system in milliseconds. No indexing delays, no waiting—just pure speed.

```
.pdf budget review
modified:week
path:projects/client
```

<p align="center">
  <img src="assets/lucidarc-search2.png?v=2" alt="Instant PDF Search" width="700">
</p>

### 💱 **Currency & Unit Conversion**
Convert currencies and units instantly without opening a browser or calculator.

```
250 USD to EUR
75kg to lbs
30°C to F
150km to miles
```

### 🧮 **Smart Calculator**
Perform complex calculations with natural mathematical expressions.

```
sqrt(144) + 50 * 2
(525 * 1.2) / 3
```

### 🌐 **AI-Powered Web Browsing**
Let AI browse the web for you and find exactly what you need. Add `?` to any web query and AI will find the unique link you're looking for.

```
web: best gaming laptops 2025?
web: github.com
web: coffee shops near me?
```

<p align="center">
  <img src="assets/lucidarc-webmode.png?v=2" alt="AI Web Browsing" width="700">
</p>

### 📋 **Intelligent Clipboard Manager**
Never lose track of your clipboard. LucidArc remembers everything you copy with:
- **Searchable History:** Find any past clip instantly
- **Pin Feature:** Keep important items at the top
- **AI Transformations:** Refactor code, translate text, improve writing, or transform data on any clip

```
clipboard:
```

### 🤖 **Natural Language AI**
Integrated AI assistant powered by LucidQuery's advanced models:
- Translate text between languages
- Draft professional emails
- Write and refactor code
- Summarize articles and documents
- Generate creative content
- Answer questions with web search

<p align="center">
  <img src="assets/lucidarc-ai.png?v=2" alt="Natural Language AI" width="700">
</p>

### ⚡ **Instant Features**
Quick access to powerful utilities:
- **App Launcher:** Launch any application instantly
- **System Commands:** Control your system without menus
- **Color Converter:** RGB to HEX and vice versa
- **Workflow Automation:** Chain commands together (Pro)
- **Text Snippets:** Expand frequently used text (Pro)

<p align="center">
  <img src="assets/lucidarc-instant.png?v=2" alt="Instant Features" width="700">
</p>

---

## Getting Started

### Installation

1. **Download LucidArc** for Windows from [lucidquery.com/lucidarc](https://lucidquery.com/lucidarc/)
2. **Run the installer** (LucidArc.exe)
3. **Launch with hotkey:** Press `Ctrl + Space` (customizable)

That's it! No account creation, no configuration required. Start typing and LucidArc instantly understands your intent.

### First Steps

1. **Press `Ctrl + Space`** to summon LucidArc
2. **Type what you want to do:**
   - File name to search
   - App name to launch
   - Calculation to solve
   - Currency to convert
   - AI prompt to execute
3. **Hit `Enter`** to execute
4. **LucidArc disappears**, letting you stay in flow

### System Requirements

- **OS:** Windows 10 (version 2004 or newer) or Windows 11
- **RAM:** 100MB minimum
- **Disk Space:** <50MB
- **Processor:** Any modern x64 processor

---

## Usage Examples

### File Search
```
.docx quarterly report          → Find all .docx files with "quarterly report"
modified:today                   → Files modified today
exact:true "Project Plan.pdf"   → Exact filename match
-dir                            → Search excluding directories
```

### Conversions
```
1000 EUR to USD                 → Currency conversion
50 miles to km                  → Distance conversion
98.6F to C                      → Temperature conversion
5 feet to meters                → Length conversion
```

### Calculations
```
15% of 250                      → Percentage calculations
sqrt(144)                       → Mathematical functions
(100 + 50) * 2                  → Complex expressions
```

### AI Commands
```
web: latest React features?     → AI browses and finds answer
"Hello" to French ?             → Language translation
Summarize: [paste article]      → Content summarization
function to sort array in py?   → Code generation
```

### Clipboard
```
clipboard:                      → View clipboard history, manage them, pin, run AI on clips in one click
clipboard: refactor             → Refactor selected code clip
clipboard: translate to Spanish → Translate any clip
```

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + Space` | Summon LucidArc |
| `Esc` | Dismiss LucidArc |
| `↑` / `↓` | Navigate results |
| `Enter` | Execute selected action |
| `Ctrl + K` | Open clipboard history |
| `Ctrl + ,` | Open settings (Pro) |
| `Tab` | Autocomplete suggestion |

*All shortcuts are customizable in Settings (Pro)*

---

## Built With

- **[Go](https://golang.org/)** - Core engine for blazing performance
- **[Wails](https://wails.io/)** - Go + Web frontend framework
- **LucidQuery AI** - Advanced AI models for natural language processing
- **Native Windows APIs** - Deep system integration


---

## Roadmap

- [x] Instant file search
- [x] Currency & unit conversion
- [x] Smart calculator
- [x] AI-powered web browsing
- [x] Clipboard manager with AI
- [ ] Plugin system for extensions
- [ ] Team collaboration features
- [ ] macOS version
- [ ] Linux version
- [ ] Custom workflows builder
- [ ] Browser extension integration

---

## FAQ

**Q: How is LucidArc different from PowerToys Run?**
A: While PowerToys Run is great for basic launching, LucidArc offers deep AI integration, intelligent clipboard management with AI transformations, advanced instant features (currency/unit conversion), AI-powered web browsing, and workflow automation. We're not just a launcher—we're an AI-powered command center.

**Q: Is my data secure?**
A: Yes. All AI communication is end-to-end encrypted. We maintain zero logs of your usage. File search happens locally on your machine. AI only runs when you explicitly request it.

**Q: Does it work offline?**
A: File search, app launching, calculator, and conversions work 100% offline. AI features require internet connection.

**Q: Can I customize the hotkey?**
A: Yes! Customize hotkeys, themes, and behavior in Settings (Pro plan).

**Q: How fast is it really?**
A: Built in Go and optimized for performance, LucidArc typically responds in <10ms for local operations (file search, launching) and <100ms for calculations. AI features depend on network latency but are heavily optimized.

---

## Support

- **Website:** [lucidquery.com/lucidarc](https://lucidquery.com/lucidarc/)
- **Issues:** [GitHub Issues](https://github.com/yourusername/LucidArc/issues)
- **Email:** contact@lucidquery.com

---

## License

LucidArc is licensed under the [MIT License](LICENSE).

---

## Credits

Built with passion by the [LucidQuery](https://lucidquery.com) team.

**AI Models:** Powered by LucidQuery's hybrid intelligence architecture

**Community:** Thanks to all our alpha testers and contributors

---

<div align="center">

**[Download LucidArc](https://lucidquery.com/lucidarc/)**

Made for Performance by [LucidQuery](https://lucidquery.com)

</div>
