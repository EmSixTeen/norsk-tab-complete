# norsk-tab-complete
Replace regular letters with Norwegian letters using tab completion. 

Made for myself to input Norwegian letters (æ/ø/å) and some diacritics used in Norwegian (ò, è and ô) on a UK ISO layout without changing my Windows language settings, but should work on any and all setups.

Created with [AutoHotKey](https://github.com/AutoHotkey/AutoHotkey "AutoHotKey"). The .exe is a direct compilation of the same code that's in the .ahk script.

------------

## To use
Open norsktabcomplete.exe, or if you'd prefer to just run the .ahk script you can do that.

Type in the longform of the letter (for example `ae`), then press `tab`. 

|Input|Result|
| :------------ | :------------ |
|AE[tab]|Æ|
|OE[tab] |Ø |
|AA[tab]|Å|
|O^[tab]|Ô|
|O'[tab]|Ò|
|E'[tab]|È|
|ae[tab]|æ|
|oe[tab]|oe|
|aa[tab]|å|
|o^[tab]|ô|
|o'[tab]|ò|
|e'[tab]|è|

### Add to startup

If you'd like the script to run on startup for you, you can add the .exe to your Windows startup folder.

To get to that folder:
1. Press `Win+R` to bring up the Run dialog
2. Type in `shell:startup` to go to the current user's startup folder
	- Alternatively, `shell:common` is the startup folder for **all** users