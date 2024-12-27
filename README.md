# Fake Virus Batch Script

This repository contains a harmless batch script that mimics the behavior of a "virus" purely for entertainment and educational purposes. **It does not harm your system or delete any data** and is intended to prank friends in a lighthearted way.

## Script Overview

### File: `virus_prank.bat`
- **Platform**: Windows
- **Description**: Simulates various "virus-like" behaviors, such as opening multiple command prompts, displaying fake error messages, or pretending to format the disk. All actions are completely reversible and harmless.

## Script Examples

### 1. Fake File Deletion
Pretends to delete files but only displays messages:
```bat
@echo off
title Deleting Files...
:loop
echo Deleting file C:\Windows\System32\drivers\important.sys...
timeout /t 1 >nul
echo Deleting file D:\Projects\MySecretFile.txt...
timeout /t 1 >nul
goto loop
```

### 2. Fake Blue Screen of Death
Changes the Command Prompt's colors and displays a critical error:
```bat
@echo off
title Blue Screen of Death
color 17
echo A critical error has occurred!
echo Please restart your computer immediately.
pause >nul
exit
```

### 3. Endless Error Messages
Continuously displays error messages to simulate a "system failure":
```bat
@echo off
:loop
msg * "Error: The system has encountered an unknown problem!"
timeout /t 2 >nul
goto loop
```

### 4. Random File Creation
Creates random text files on the desktop:
```bat
@echo off
:loop
echo You’ve been hacked! > "%userprofile%\Desktop\Hacked_%random%.txt"
timeout /t 1 >nul
goto loop
```

### 5. Fake Keylogger Simulation
Displays a fake "keylogger" activity log:
```bat
@echo off
echo Keylogger activated...
timeout /t 2
echo Scanning keystrokes...
timeout /t 2
echo Recording data... (Just kidding!)
pause
```

## How to Use

1. Copy one of the script examples above into a text editor (e.g., Notepad).
2. Save the file with a `.bat` extension (e.g., `virus_prank.bat`).
3. Double-click the file to run it.
4. To stop the script:
   - Press `Ctrl + C` in the Command Prompt and type `y` to terminate.
   - Alternatively, open Task Manager (`Ctrl + Shift + Esc`) and end all instances of `cmd.exe`.

## Disclaimer
- These scripts are intended for **personal use and educational purposes only**.
- Do not run these scripts on someone else's computer without their explicit permission.
- Misusing these scripts may lead to unintended consequences and could violate ethical or legal guidelines.

## License
This project is licensed under the MIT License. Feel free to modify and use responsibly!
