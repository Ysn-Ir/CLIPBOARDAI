<div align="center">
  <h1>🤖 ClipboardAI</h1>
  <p><b>Your Universal AI Clipboard Assistant</b></p>
  <p><i>Transform text anywhere on your computer instantly using Groq, Gemini, OpenAI, or local Ollama models.</i></p>

  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
  [![Python 3.12+](https://img.shields.io/badge/python-3.12+-blue.svg)](https://www.python.org/downloads/)
  [![CustomTkinter](https://img.shields.io/badge/UI-CustomTkinter-darkgreen)](https://github.com/TomSchimansky/CustomTkinter)
</div>

<br/>

ClipboardAI is a lightweight, background-running Windows desktop application that intercepts your clipboard text, processes it through advanced AI models, and instantly replaces it with the AI's response. Whether you need to explain complex code, translate languages, or debug errors, ClipboardAI acts as a universal bridge between your workflow and AI.

---

## ✨ Features

* **🔌 Multi-Backend Support**: Use lightning-fast **Groq**, generous free-tier **Google Gemini**, standard **OpenAI**, or completely private offline **Ollama**.
* **🥷 Silent Background Operation**: Sits quietly in your Windows System Tray until you call it via global hotkeys.
* **⚡ Instant Execution**: Highlight text in *any* application, hit a hotkey, and watch the text get replaced with the AI's output.
* **🛠️ Custom Modes**: Create your own custom AI personas, prompts, and hotkeys using the built-in Modes editor.
* **🌐 Web Search Integration**: Toggle web search on specific modes to give the AI up-to-date context from the internet before it answers.
* **🎨 Modern UI**: A sleek, dark-themed settings dashboard built with `customtkinter`.

---

## 🚀 Installation & Download

### Option 1: Quick Install (Recommended)
1. Go to the **[Releases](../../releases)** page.
2. Download the latest `ClipboardAI_Setup_vX.X.X.exe`.
3. Run the installer.
4. Launch ClipboardAI from your Start Menu!

### Option 2: Portable Version
1. Download `ClipboardAI.exe` from the latest Release.
2. Place it in any folder and double-click to run.

---

## ⚙️ Setup & Configuration

When you first open the app, you need to configure an AI backend:

### If using Cloud APIs (Groq, Gemini, OpenAI)
1. Open the app and go to the **API Keys** tab.
2. Paste your API key for your preferred service (Links to get free keys are provided in the app).
3. Click **Test** to verify it works, then **Save Keys**.
4. Go to the **Settings** tab, select your Backend and Model, and click Save.

### If using Local Ollama (100% Private & Free)
1. Ensure the [Ollama](https://ollama.com/) app is running on your computer.
2. Go to the **Settings** tab in ClipboardAI.
3. Change the Backend to **Ollama**.
4. Click **Discover Models**. The app will detect your installed models (like `llama3`, `mistral`, etc.).
5. Select your desired model and click **Save Settings**.

---

## ⌨️ Default Hotkeys & Usage

Using the app is incredibly simple. Just highlight any text, copy it (`Ctrl+C`), and press one of your hotkeys:

| Mode | Default Hotkey | What it does |
| :--- | :--- | :--- |
| **Explain** | `Ctrl + Alt + Space` | Explains the copied text in simple, plain language. |
| **Code** | `Ctrl + Alt + C` | Takes your instruction and writes production-ready code. |
| **Fix** | `Ctrl + Alt + F` | Debugs the copied code/error and returns the fixed version. |
| **Translate** | `Ctrl + Alt + T` | Translates the copied text into English. |
| **Undo** | `Ctrl + Alt + Z` | Reverts your clipboard back to the original text if you don't like the AI output. |

*(All hotkeys and prompts are fully customizable in the **Modes** tab!)*

---

## 🛠️ Building from Source

If you want to modify the code and build your own executable:

1. Clone the repository:
   ```cmd
   git clone https://github.com/Ysn-Ir/AI-COPY-PASTE-APPLICATION-DESKTOP.git
   cd AI-COPY-PASTE-APPLICATION-DESKTOP
   ```
2. Install dependencies:
   ```cmd
   pip install -r requirements.txt
   ```
3. Run directly:
   ```cmd
   python main.py
   ```
4. Build the executable (`.exe`):
   ```cmd
   build.bat
   ```

---
<div align="center">
  <i>Built with Python, CustomTkinter, and pynput.</i>
</div>
