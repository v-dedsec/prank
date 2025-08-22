# Windows Text-to-Speech Prank 🎙️

This is a simple **Windows batch script** that uses PowerShell’s built-in text-to-speech engine to say a message out loud when the file is executed.

## 🚀 How it works
The batch file calls PowerShell and uses the `SAPI.SpVoice` COM object to make the computer speak a predefined message.

Example included:
```bat
@echo off
PowerShell -Command "(New-Object -ComObject SAPI.SpVoice).Speak('You have been hacked')"
exit



When you double-click the batch file, Windows will say:
"You have been hacked"


⚠️ Don’t worry — this does not actually hack your computer, it’s just a harmless text-to-speech prank.

# 📦 Setup
Clone this repository or download the .bat file.
Double-click the .bat file.
Listen to your computer speak the message.

# 🎯 Customization
You can change the spoken message by editing the .bat file and replacing:
'You have been hacked'
with any phrase you want.

Example:
PowerShell -Command "(New-Object -ComObject SAPI.SpVoice).Speak('Hello World')"

# ⚠️ Disclaimer
This is intended for educational and fun purposes only.
Do not use it in ways that could scare, harass, or mislead others.
