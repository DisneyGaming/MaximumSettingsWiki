# Grand Theft Auto: V
---
## Status - <span style="color:green">Working</span>(Caveats)

Grand Theft Auto: V is playable on MaximumSettings and Linux due to how the Anti-Cheat works. GTA:V doesn't load the anti-cheat until you load online. due to unknown reasons online works with the anti-cheat. This doesn't mean it is recommended, some communities consider virtualisation as a way to cheat Anti-Cheat due to what it is. Although there isn't any confirmed cases of being banned there is always the risk of being banned. You have been warned.

Source: [ProtonDB](https://www.protondb.com/app/271590)

## Mods
---
Grand Theft Auto: V has an active mod community ranging from simple Single-player Mod Menus to full online replacements (Five:M). Due to how the translation layer (WINE) works, mods are very hit and miss. Basic Mods work like single-player mod menus but things that require specialty tools Like Five:M, RageCOOP, LCPDFR, amongst more complex mods do not work. 

### How to install mods
---
To install mods you will need to change a setting relating to how WINE the translation layer handles DLLs.


=== "Lutris"

    Firstly, Open Lutris and right click on Grand Theft Auto: V and press Configure.

    A window will appear, next click on [Runner Options](https://i.imgur.com/m2miplz.png) scroll down to the bottom to DLL Overrides.

    Press add and type "dinput8" into the key and "n,b". Once typed in press save.

    Your basic mods should work. There is no guarantee that your mods will work on Linux, MaximumSettings are unable to support you.


=== "Proton/Steam"

    Firstly, Install a piece of software called [Protontricks](https://flathub.org/apps/com.github.Matoking.protontricks)

    Once installed, make sure GTA:V is installed then type the following command. ```protontricks 271590 winecfg``` then hit enter.

    After a short amount of time a window should pop up revealing the Wine Configuration tool, From here hit the [Libraries](https://i.imgur.com/Ca6dd6S.png) tab then click on "new override for library" then type in dinput8 and press add.

    Press "Apply" then "Ok".

    Your basic mods should work. There is no guarantee that your mods will work on Linux, MaximumSettings are unable to support you. 

=== "Bottles"

    Firstly, Open Bottles then click on the bottle which contains the Grand Theft Auto: V installation.

    Then press the Options button which should take you to where you can configure things from language to WINE Runner.

    Now, scroll down until you see [DLL Overrides](https://i.imgur.com/ZuvrYJE.png) Press on the button to open the tab.

    Afterwards, type in the "New Override" input box "dinput8" then press the plus button.

    Finally, close the tab and open Grand Theft Auto: V

    Your basic mods should work. There is no guarantee that your mods will work on Linux, MaximumSettings are unable to support you. 


### FiveM
FiveM as said previously is a Grand Theft Auto: V online replacement mod which allows for the user to join many different servers ranging from simple roleplay to things like zombie survival. 

Due to the complexity of the mod it is not possible to play it on Linux due to how the mod uses windows to help with graphics which are not possible with WINE. This is not likely to change at the time being.

Source: [FiveM FAQ](https://docs.fivem.net/docs/support/client-faq/#will-fivem-run-on-linux)