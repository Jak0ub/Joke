## WORKS ONLY ON WINDOWS

## SHA-256
```
0F933B9EF86980E02A102AA3CEEBCD0B58102DAD09925ADE6930CA1E1A201637
```
> ℹ️ **Recommendation:**
> If you are unsure whether Python is present on the victim's computer, you can use PyInstaller to create an .exe file from a .py file.

## How to delete the program after activation
```
del "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup\troll.vbs"
```
> ⚠️ **Warning:**
> Administrator privileges will be required for deletion, so run the cmd as administrator
> 
`Your system partition letter may vary`

## Description
Each time the PC is turned on, the file troll.vbs will start, and it can only be turned off using taskkill.


> ℹ️**Information:**
> The VBS process can also be terminated using a file available [on this GitHub](https://github.com/Jak0ub/Process-Killer)

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
