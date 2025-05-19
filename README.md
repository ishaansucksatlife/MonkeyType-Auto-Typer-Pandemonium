Pandemonium Auto MonkeyType 💻⌨️
 
A browser automation tool for [MonkeyType](https://monkeytype.com) that simulates typing with realistic delays, accuracy settings, and fully customizable hotkeys.

> 💻 Built by **Plasma**

------

## ⚠️ Note

🪟 **This tool is Windows-only.**  
It relies on the `keyboard` module, which does not support macOS or Linux for full hotkey functionality.  

Ensure you're running it on a Windows machine for best results.

## 🔥 Features

### 🧠 Realistic Typing Simulation  
Mimics natural human typing with variable speeds, typos, and auto-correction using backspace.

### ⌨️ Custom Hotkey Support  
Bind your own keys to Start, Pause, Resume, and Stop.

### 🎯 Accuracy Control  
Configure typing accuracy (e.g., 95% accuracy = 5% intentional typos).

### 🕹️ Zen Mode Support  
Supports continuous typing and auto-scroll in MonkeyType’s infinite mode.

### 🖥️ Browser Automation  
Reads the active word directly from the MonkeyType test via live DOM parsing.

### 📈 Speed Settings  
Set min/max delay between key presses (in milliseconds).

### 🎛️ GUI-Based Configuration  
No need to touch the code! Adjust all settings through a sleek interface.

### 🔄 Restartable Typing  
Pause, resume, or stop at any point with hotkeys or GUI buttons.

---

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
pip install -r requirements.txt

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
## 📄 License
This project is licensed under the MIT License.

[MIT](https://choosealicense.com/licenses/mit/)

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
