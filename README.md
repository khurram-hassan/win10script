# Declaration
I forked this project from Chris Titus Tech's [Github project](https://github.com/ChrisTitusTech/win10script/tree/master)]. I like his work and wanted to modify this script according to my need.

# win10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine.

## Powershell Run As ADMIN
Open powershell as Administrator and copy paste below code and press Enter to download and execute this script on your Windows PC.
```
iex(New-Object Net.WebClient).DownloadString('https://git.io/JJoh5')
```

## My Additions

- ~~Dark Mode~~
- One Command to launch and run
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Added Debloat Microsoft Store Apps

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
