Requirements:
 * If you are running on Windows 7, you may need to download the
   "Microsoft Visual C++ 2015 Redistributable Update 3"
   https://www.microsoft.com/en-us/download/details.aspx?id=53587
 * If you are running on Windows Server, you will need XINPUT1_3.DLL
 * If you do not have write access to your GTA directory, you will need to run Infamous as Administrator.



How to Use:
  * Extract the Infamous RAR file to a directory somewhere, it doesn't go in the GTA directory.  Put it on your desktop or something.  Don't move any files to the GTA directory, just leave them all in a nice little directory of their own.
· Start Infamous.exe
· Wait until GTA started
· Go into Story Mode
· Press F4 and it should work now

Alternate Way:
· Start GTA V
· Go into Story Mode
· Start Infamous.exe
· Press F4 ingame and it should work now

Hotkeys:

Keyboard:
· F4 – show/hide menu
· Numpad 8/2/4/6 – menu up/down/left/right
· Numpad 5 – menu select
· Numpad 0 – menu back
· Numpad-9 – vehicle boost (if enabled)
· Numpad-3 – vehicle instant stop (if enabled)
· Numpad-Add – vehicle rockets (if enabled)
· Ctrl – Numpad-Divide – teleport forward slightly (i.e. through a door)
· F6 – airbrake mode
· Numpad-Subtract – Teleport to Mission Objective/Checkpoint/Marker

Controller:
· RB (Right Shoulder) + D-Pad Left: activate menu
· D-Pad: navigate menu
· A: menu select
· B: menu back
· RB (Right Shoulder) + D-Pad Right: activate airbrake
· Vehicle boost: RT (Right Trigger) + D-Pad Up
· Vehicle stop: LT (Left Trigger) + RB (R shoulder)
· Vehicle weapons: L shoulder

You can redefine these themselves using the XML file, which contains more info and should be self-explanatory.

# Troubleshooting:

 *  Did you extract the files from the RAR file, into their own directory (not into the GTA directory)?
 *  Have you tried running Infamous.exe as Administrator? 
    https://helpx.adobe.com/x-productkb/global/run-program-administrator-windows-7.html
 *  Have you installed "Microsoft Visual C++ 2015 Redistributable Update 3"? 
    https://www.microsoft.com/en-us/download/details.aspx?id=53587
 *  Have you run GTA without Infamous, and ensured the game is functional?
 *  Is there a file in your Infamous folder called "infamous.dll" (if not, work out why not)
 *  Are you loading Single Player when GTA starts?  You should always load into Single Player first, 
    you should set it as the default option. http://i.imgur.com/0pwvu5W.png


Q: It says I am missing some dll files.
A: Download these dll files from google and put them into windows/system32 and/or into the Infamous Folder

Q: The code execution cannot proceed because MSVCP140.dll was not found.
Q: The code execution cannot proceed because VCRUNTIME140.dll was not found.
A: Download "Microsoft Visual C++ 2015 Redistributable Update 3"
   https://www.microsoft.com/en-us/download/details.aspx?id=53587

Q: I have both Steam and SC version installed, can I make the Injector un the Steam version instead?
A: Rename the registry key `SOFTWARE\Wow6432Node\Rockstar Games\Grand Theft Auto V` to something else

Q: Injector says "infamous successfully injected!" but I can't open the menu ?
A1: If you have a modified your GTA5.exe please get a clean exe. Otherwise it won't work
A2: Make sure you tried every way to inject it into the game from "How to Use" and also started into Story Mode,
if this doesn't work try using Xtreme Injector.

Q: Still nothing works, what do I do wrong ?
A: If Infamous Injector and Xtreme Injector both don't work you probably are missing
Visual C++ Redistributable for Visual Studio 2015. Download and install it and try again.

Q: I tried that too but it still doesn't work ):
A: There might be a problem with Windows UAC. Deactivate it and see if that fixes your problem.

Q: Nothing of your previous answers helped me!
A: Then we can't help you anymore. There might be something with your computer which prevents it.

Q: Can't get pass login screen
A: You can edit your credentials file manually.
```
c:\users\sfink\appdata\Roaming\Infamous GTAV Menu\inf-cred.ini
```

```
[INFCRED]
remember=1
username=JoeUser
password=xxxxxxx
autologin=1
```

Q: Message about Windows SmartScreen is displayed 
A: When the message about Windows SmartScreen is displayed on installing or executing a software, please perform the following procedures.
        Click the [ More info ].
        Click the [ Run anyway ].

* Misc Information

File Locations
 -  C:\Users\YOURNAME\AppData\Roaming\Infamous GTAV Menu
     -  infamous.db - your infamous settings
	 -  inf-cred.ini - your account credentials
	 -  inf-config.xml - permanent copy of your custom keyboard/controller shortcuts (copy from Infamous directory if you want to keep you settings between releases)


	 
Credits:
· Infamous Dev Team (John Doe, Jane Doe, John Smith, James Smith)
· https://www.infamouscheats.cc/


============================================================================
Note for future releases. The always current link to the latest MSVC:
https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads

Here are some more direct links.
Microsoft Visual C++ Redistributable for Visual Studio 2017
https://aka.ms/vs/15/release/vc_redist.x64.exe

Microsoft Visual C++ 2015 Redistributable Update 3
Direct link: 
https://download.microsoft.com/download/6/D/F/6DF3FF94-F7F9-4F0B-838C-A328D1A7D0EE/vc_redist.x64.exe
