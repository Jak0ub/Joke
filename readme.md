## WORKS ONLY ON WINDOWS
## How to delete the program after activation
```
del "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup\troll.vbs"
```
> ⚠️ **Warning:**
> Administrator privileges will be required for deletion, so run the cmd as administrator
`Your system partition letter may vary`
## SHA-256
SHA-256
```
170065E873947F070611F1DCA719122B79A289C23E30EE94DA448262ECB4B15C
```
> ℹ️ **Recommendation:**
> If you are unsure whether Python is present on the victim's computer, you can use PyInstaller to create an .exe file from a .py file.

## Description
Each time the PC is turned on, the file troll.vbs will start, and it can only be turned off using taskkill.


> ℹ️**Information:**
> The VBS process can also be terminated using a file available on this GitHub. On my profile, there is a file for terminating processes specified by you.
```
taskkill /IM "wscript.exe" -F
```
> ⚠️ **Warning:**
> Administrator privileges will be required by the victim.

## Python to Executable

```
pip install pyinstaller
```
`Installing PyInstaller`
```
pyinstaller --onefile file.py
```
`The .Exe file is now located in \dist\file.exe`
