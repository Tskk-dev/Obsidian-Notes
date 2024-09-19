**CHUNITHM SUN INSTALL GUIDE** 
_tl;dr Download game and aqua Setup segatools Launch aqua and game._ **GUIDE UPDATED 09.04.2023** **Installation** 

**1.** Get the files from Pixeldrain ([https://pixeldrain.com/u/QzJd84an](https://pixeldrain.com/u/QzJd84an "https://pixeldrain.com/u/QzJd84an")) 
**2.** Download latest aqua ([https://mega.nz/file/qxJhSCZa#FmiEgqV9bP-LixY-CFishEIEGCu3Gv8LBtiaAN6AqvY](https://mega.nz/file/qxJhSCZa#FmiEgqV9bP-LixY-CFishEIEGCu3Gv8LBtiaAN6AqvY "https://mega.nz/file/qxJhSCZa#FmiEgqV9bP-LixY-CFishEIEGCu3Gv8LBtiaAN6AqvY")) 
**3.** Download official option files([https://pixeldrain.com/u/F4nVVedf](https://pixeldrain.com/u/F4nVVedf "https://pixeldrain.com/u/F4nVVedf")) 
**4.** Extract everything.
**5.** Download the bin folder with patched exes and segatools([https://pixeldrain.com/u/7aHPwnaU](https://pixeldrain.com/u/7aHPwnaU "https://pixeldrain.com/u/7aHPwnaU"))
**6.** Copy and replace all the files from the archive to your bin folder than contains ChusanApp.exe, copy the A001-A151 to bin/option 
**7.** If you don't have/want 120hz support patch with CVT mode. ([https://patcher.turksigara.net/chusun.html](https://patcher.turksigara.net/chusun.html "https://patcher.turksigara.net/chusun.html"))
**8.** Open segatools.ini find [dns] and 'default=' 
**9.** Type ipconfig in cmd and look for "IPv4 Address: ", probably starts with 192.168.x.x
**10.** Write the IP address you got after the 'default=' symbol like 'default=192.168.100.1' **11.** Done

**Controls** 
If you are using the keyboard, which is probably the worst way to play but a possible one, launch auqa using start.bat, launch the game using start.bat and you are done. The default input is SDFJKL, 1 for test menu, 2 for service button and coin inserting, holding enter scans a card. If you want to change the keyboard input, change the cells in [slider] in segatools.ini acording to [https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes](https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes "https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes") If you are using a Tasoller, make sure you have FW2.0, if not upgrade to 2.0, check djdao site for guide. If your Tasoller arrived in 2022 or 2023 it wil have FW2.0 most probably. Your Tasoller should be auto detected by the game and working OOB. Same as above applies to Yubideck owners. If you have FW1.0/1.1 you can use ([https://github.com/CrazyRedMachine/chu2to3](https://github.com/CrazyRedMachine/chu2to3 "https://github.com/CrazyRedMachine/chu2to3")) and chuniio for paradise lost to run your Tasoller altough that's not recommended. If you are using Brokenithm iOS, join the testflight to download the controller app ([https://testflight.apple.com/join/15FSg9sB](https://testflight.apple.com/join/15FSg9sB "https://testflight.apple.com/join/15FSg9sB")) Download Brokenithm iOS client ([https://pixeldrain.com/u/BpDzs3yv](https://pixeldrain.com/u/BpDzs3yv "https://pixeldrain.com/u/BpDzs3yv")) Connect your device Launch the brokenithm exe Done. 

**Launching** 
EVERYTIME before you launch the game, check if 
**1.** Your resolution IS **1080P**, NOT LOWER NOT HIGHER, if It isn't change it, **Chunew expects 1080p and only 1080p.** 
**2.** Your CD/DVD drive IS DISABLED. 
**3.** You launched Brokenithm exe if using brokenithm If these three things are set, open the aqua server you extracted in Step 
4, then open your game USING START.BAT IN THE BIN FOLDER, the aqua server needs to be opened everytime your game is launched if you want to save scores.


 **Troubleshooting** 
 
**Error 6401** - Your resolution is not 1080p, change it, this should be patched out in Sun altough if you enconter this stil try changing to 1080p@120hz/60hz.
 
**Error 0919** - Disable your DVD Drive

**Error 0800** - Unknown Error, only John Sega what happened here. **Aime connection failing** - check [dns] in segatools and your ip, they must match

**Can't play ranking mode** - your amfs is messed up or you didn't change application.properties in aqua to match your chunew version 

**Other errors - Use Google Translate and translate them, most of the times they are simple to fix if you translate them.**

**Options** There are few options available that add removed/unreleased charts ,

**ASAN** - Contains content from Chunithm NEW+ that was removed in SUN 

**ANEW** - Contains content from Chunithm NEW that was removed in NEW+

**A114** - Omnimix, it adds everything that was ever deleted, sound quality thanks to audio changes in NEW isn't great. 

**AS01/AS02/AS03** - Contain new charts(Performai, Arcaea, Deco*27, April Fools charts) ported from International. Download them from discord or pixeldrain([https://pixeldrain.com/l/EfpQ5KKK](https://pixeldrain.com/l/EfpQ5KKK "https://pixeldrain.com/l/EfpQ5KKK")) and put them in option folder.

**English Translation** There's an English translation available, it translates almost the entirety of Chunithm SUN to English language. Including TestMenu, Skills, Tutorial, UI etc. You can get it from ⁠_Unknown_ or [https://pixeldrain.com/u/T3bYzS8q](https://pixeldrain.com/u/T3bYzS8q "https://pixeldrain.com/u/T3bYzS8q")


misc:
set this in  config_common.json
`"allnet_accounting" :     {         "enable" : true,         "mode" : "A"     }`

![[Pasted image 20231022003446.png|Pasted image 20231022003446.png]]![[Pasted image 20231022003452.png|Pasted image 20231022003452.png]]