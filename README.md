# 🦀 Essay-CLI

A command-line tool written in **Rust** that helps you **generate, write, and evaluate essays** — fully integrated with **Ollama** for topic generation and feedback.

---

## ✨ Features

- 🎯 **Smart Topic Generator** – instantly get an essay topic from your local Ollama model (e.g. Mistral, Llama 3, etc.)  
- ⏳ **Writing Timer** – built-in timer system to track your focused writing sessions  
- 📝 **Essay Editor** – write and save your essay directly from the CLI  
- 🤖 **AI Feedback** – send your essay to Ollama for evaluation and receive structured feedback (grammar, coherence, argument quality)  
- 💾 **Local Storage** – essays saved automatically to a local directory with timestamps  
- ⚙️ **Customizable Models** – choose which Ollama model to use

---

## 🧱 Architecture Overview

| Module | Description |
|:--------|:-------------|
| `src/main.rs` | Entry point, handles command-line arguments |
| `src/ollama.rs` | Communication with the Ollama local API (`localhost:11434`) |
| `src/timer.rs` | Implements countdown and stopwatch timers |
| `src/editor.rs` | Manages essay writing and saving |
| `src/feedback.rs` | Sends essay text to Ollama for review |
| `src/utils.rs` | Formatting, time handling, and helper utilities |

---

## 🧰 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/OgShadoww/essay-cli.git
cd essay-cli

