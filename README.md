Pandemonium MonkeyType Auto Typer 💻⌨️
 
A browser automation tool for [MonkeyType](https://monkeytype.com) that simulates typing with realistic delays, accuracy settings, and fully customizable hotkeys.

> 💻 Built by **Plasma**

------

## ⚠️ Note

⚠️ **This tool is Windows-only.**  
It relies on the `keyboard` module, which does not support macOS or Linux for full hotkey functionality.  

Ensure you're running it on a Windows machine for best results.

## 🛡️ Safety & Assurance

We understand that downloading `.exe` files can be a concern for many users. That's why we prioritize transparency and user trust.

✅ The executable file `PandemoniumAutoMT.exe` has been scanned and verified to be safe.

🔗 **VirusTotal Scan Report:** [Click here to view the results](https://www.virustotal.com/gui/file/a18738008a78a24a815758dd88a1449801bf02f1a7e518e123c9dfb5412e5921?nocache=1)

> This scan confirms that the file contains no malware, spyware, or malicious behavior.

Some antivirus engines may flag this tool due to its automation capabilities and the way it's packaged as a `.exe`. Rest assured:
> These are generic heuristic tags:

Kryptik: Often flags tools that simulate or automate inputs, key presses, etc.

Tool.DDoS.Script.1: It's flagging your MonkeyType auto-typer as a script capable of "sending repeated requests" (even though it's just simulating typing).

Malicious/Suspicious PE: Based on AI/static heuristics — no actual virus found.

> - No malicious behavior exists in this project.

For additional peace of mind:
- The source code remains private to prevent tampering and unauthorized edits.
- Only use the official executable from our [GitHub releases](https://github.com/ishaansucksatlife/MonkeyType-Auto-Typer-Pandemonium/releases) to ensure safety.

If you have any doubts or questions, feel free to ask in our [Discord Support Server](https://discord.com/invite/HazvsVHxyE).


## 🔥 Features

### 🧠 Realistic Typing Simulation  
Mimics natural human typing with variable speeds, typos, and auto-correction using backspace.

### ⌨️ Custom Hotkey Support  
Bind your own keys to Start, Pause, Resume, and Stop.

### 🎯 Accuracy Control  
Configure typing accuracy (e.g., 95% accuracy = 5% intentional typos).

### 🖥️ Browser Automation  
Reads the active word directly from the MonkeyType test via live DOM parsing.

### 📈 Speed Settings  
Set min/max delay between key presses (in milliseconds).

### 🎛️ GUI-Based Configuration  
No need to touch the code! Adjust all settings through a sleek interface.

### 🔄 Restartable Typing  
Pause, resume, or stop at any point with hotkeys or GUI buttons.

---

## 📦 Requirement 

To run **PandemoniumAutoMT.exe**, you'll need:

- Python 3.8+ installed
- Google Chrome browser
- The following Python packages:

```txt
selenium
keyboard
webdriver-manager

```

### To install all dependencies, run this command:
```bash
pip install -r requirements.txt
```
---
## 🚀 How It Works

- Runs locally on your PC
- Opens Chrome using Selenium and loads [MonkeyType](https://monkeytype.com)
- Waits until you focus the input field
- Automatically types the current test based on your config
- Works with all test types: Words, Time, Quote, Zen

---
## 🧪 How To Use

### ✅ (`PandemoniumAutoMT.exe`)

1. Double-click `PandemoniumAutoMT.exe` to run the program.
2. Wait for Chrome to open MonkeyType.
3. Use the GUI to set delay, accuracy, and custom hotkeys.
4. Click inside MonkeyType’s typing field.
5. Press your chosen **Start hotkey** or use the **Start Typing** button.

---
## ⚙️ Configuration Options

| Setting        | Description                                |
| -------------- | ------------------------------------------ |
| Min Delay (ms) | Minimum time between key presses           |
| Max Delay (ms) | Maximum time between key presses           |
| Accuracy (%)   | Typing accuracy (typos are auto-corrected) |
| Start Hotkey   | Begin typing                               |
| Resume Hotkey  | Resume after pause                         |
| Pause Hotkey   | Temporarily stop typing                    |
| Stop Hotkey    | Terminate typing entirely                  |

## 🧩 Supported Modes
• 📝 Words Mode

• ⏱️ Time Mode

• 📖 Quote Mode
## 📁 Included Files

• PandemoniumAutoMT.exe – Precompiled executable (for Windows)

• requirements.txt – List of required Python libraries

• README.md – Project documentation

---

## 📄 License
This project is not open source.
The executable (PandemoniumAutoMT.exe) is provided for personal and non-commercial use only.

You may not:

Reverse-engineer, decompile, or modify the executable

Redistribute it without proper credit

Use it for commercial purposes without permission

📌 This project is proprietary software. No source code is available to tbe public yet.
---

## 💬 Need Help?

Join our **Discord Support Server**:  
👉 [Pandemonium](https://discord.com/invite/HazvsVHxyE)

We’re happy to help with:

- 🐛 Bug reports  
- 💡 Feature suggestions  
- 🙋 General support

---

## 💻 Made by Plasma

_"Because sometimes you just need to beat your own score."_

**Follow me online:**  
🔗 GitHub – [@ishaansucksatlife](https://github.com/ishaansucksatlife)

📱 Discord - [Pandemonium](https://discord.com/invite/HazvsVHxyE)
