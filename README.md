# Cloud Client FAQ
Unofficial FAQ for Cloud Client, maintained by [JuxGD, AKA replicat](https://github.com/JuxGD).

## Credits
[CREDITS.md](https://github.com/JuxGD/cloudclient-faq/tree/master/CREDITS.md) contains all the credit for stuff currently in this repo.

## Usage
Link this FAQ to anyone asking a question about Cloud Client and tell them to CTRL+F to search what they're looking for.

I will expand this as time passes, according to what people are frequently asking about Cloud Client.

- **Q: What is Cloud Client?**  
Cloud Client is a free and open-source PvP client for Minecraft: Java Edition (known in 1.7 to 1.12 as simply "Minecraft"), available for Forge Mod Loader for versions 1.7.10, 1.8.9 and 1.12.2. It is developed and maintained by duplicat, the only developer, who is currently rewriting the project. Cloud Client is currently in beta.  
You can find all of the Cloud Client links [here](https://cloudmc.dev). There's a Discord, the GitHub repositories for the mod and the installer (installer currently only for Windows, 1.12.2 not supported yet), and more. **These links, and all the links past this point are the ONLY official links unless stated otherwise.**

- **Q: What does "free and open source" mean?**  
It means that you can see and compile the code yourself. You can also contribute to the project by forking it, changing it and making a pull request. You also get a lot of freedom over what you can do with Cloud Client (as long as you follow the license, more info below).

- **Q: What is Cloud Client's license?**
Cloud Client is licensed under the GNU Lesser General Public License, version 3.0 (AKA LGPLv3). You can do whatever you want with Cloud Client and its source code, AS LONG as you follow LGPLv3.  
LGPLv3 is an extension of the normal, base GNU General Public License, version 3.0 (GPLv3).

- **Q: Is Cloud Client malware?**  
No. The [Cloud Client installer](https://github.com/CloudClientDev/cloudinstaller) is detected by many antivirus services (VirusTotal, MalwareBytes) as malware. This is a false positive. You'll commonly see this with many installers. Installers perform automated tasks on your computer to install a program. Of course, installers can be bad, which is why you must trust them first. You can trust the Cloud Client installer, it's also open source, you can look at the source code for the installer yourself.
Cloud Client itself is also not malware, it's not spying on you or anything, you're good. If you're skeptical, check the source code, or ask someone trustworthy to do it for you if you can't read Java code. If you're still skeptical after that, get the source code that *you know is safe*, and build it yourself.

- **Q: How do I install Cloud Client?**  
If you're on Windows, you can use the installer. If you want Cloud Client for 1.12.2, you want to install it manually, or if you're on Mac, Linux, some other OS, you'll need to get the mod itself.  
The installer will first check if you have Forge ModLoader installed for the version you want. If it is, the process might pause and you'll have to click the button again. If not, it will download and run the Forge installer. A window will pop up, select "Install client", change your Minecraft directory if necessary, and click OK. After making sure Forge is installed, it will download Cloud Client and put it in your minecraft/mods folder. You're done! If using a profile-based launcher like the default one, I recommend going to the mods folder and creating a folder inside it, named after the Minecraft version you installed Cloud Client for (if you installed it for 1.8.9, the directory structure will be minecraft/mods/1.8.9), and then putting the cloud .jar file in the new folder. This is to avoid conflicts with other mods.
To download and install the mod manually, go to the GitHub repository for Cloud Client, go to the Tags section, and click on the release you want (i recommend the latest Cloud Client release for the Minecraft version you'll play). Then, click on Assets if it's not showing the files. There will be three files, the .jar file, which is the mod, and the source code in 2 different formats. You want to get the .jar file. Click it, and it will download it. DO NOT run it, Forge will take care of that. Go to the [official Minecraft Forge page](https://files.minecraftforge.com/) and click on the Minecraft version you want in the sidebar. Then, click on either of the "Installer" buttons. You might be shown some ads, ignore them and click skip on the top right corner. The Forge installer will download!



- **Q: Does Cloud Client include Replay Mod?**  
No. Replay Mod is licensed unther GPLv3, while Cloud Client is licensed under LGPLv3. GPLv3 states that you may only convey software if it keeps the same license. Cloud Client isn't GPLv3 (or well, yes, but it's also LGPLv3 which changes it, so no), so including Replay Mod would violate the license. However, Replay Mod is publicly available for download [here](https://github.com/ReplayMod/ReplayMod), and thanks to Cloud Client being a Forge mod, it can be used along Replay Mod.  
Be aware that there's currently some compatibility issues with it. You'll be able to record replays, but you can't play them. You must temporarily disable/uninstall Cloud Client and restart your game to be able to play the replays. When you're done, enable/install Cloud Client once again and restart your game. Your HUD and config won't be deleted when disabling/uninstalling Cloud Client, once you put it back it'll work as it did before.

- **Q: Does Cloud Client include OptiFine?**  
No. The OptiFine license doesn't allow anyone to include OptiFine in any mod or modpack. To respect the license, duplicat can't include OptiFine in Cloud Client. He'd have to directly ask the OptiFine developer if he can include it or not. However, OptiFine is also available for download [here](https://optifine.net/downloads). If you want to support sp614x, the OptiFine developer, click the Download button for whatever version of Minecraft you play. You'll be shown some ads. The "(Mirror)" button is a direct download.

- **Q: Does Cloud Client support cracked/pirated/non-premium?**  
Yes and no. You can play on cracked Minecraft, it'll work fine, BUT no one on GitHub or Discord, especially the staff team and duplicat, will help you with problems you might have with Cloud Client. In short, you can play on cracked, but you won't get help.

- **Q: Does Cloud Client have FPS boost and performance optimizations?**  
Not currently. Add mods like OptiFine, FoamFix, TexFix, etc. to your game yourself, and it'll go a little easier and smoother on your device. Not that Cloud Client reduces FPS that much, tho. Since it's lightweight, you'll get about the same FPS as in vanilla Minecraft or Forge with no mods.

- **Q: What mods does Cloud Client have?**  
  All of these mods are divided into categories in the client, for ease of discovery.  
  - ToggleSprint
  - ToggleSneak
  - FPS display
  - Keystrokes
  - Armor Status
  - Fullbright
  - Snaplook (hold to 3rd person)
  - Coordinates
  - Server Address
  - Ping display
  - CPS display (included in Keystrokes)
  - Potion Status
  - Time (real-time clock)
  - Speed Indicator
  - 1.7 animations
  - Freelook (banned on many servers, most importantly Hypixel Network, use with caution)
  - Crosshair
  - Motionblur
  - GUI Tweaks (blur background, darken background)
  - Block Overlay (change block outline and fill when looking at it)
  - BlockInfo (like NEI; look at a block and get info about it)
  - Reach Display
  - Zoom
  - Day Counter
  - NoHurtCam
  - ScrollTooltips (if an item's tooltip is too big, you can scroll)
  - ParticleMultiplier
  - NickHider (changes your name to You or a custom name. everyone in the game will see your normal name)
  - Scoreboard (move it around, change the font, remove red numbers)
  - Bossbar
  - Direction (look at your yaw, like lunar client's Compass mod)
  - Hit Color
  - Time Changer
  - NameTag (show your nametag in 3rd person, change opacity, size, height, etc.)

  There's also some more customizablility that could be considered as mods, but they're not in the mods tab.  
  - Font Changer (change Cloud Client GUI font to any font in your computer. don't make it a very large one)
  - Color Changer (change Cloud Client GUI color)
  - Minimal View Bobbing (the held item, or hand, will bob as you move, but your camera will stay in place)
  - Fire Height
  - Custom Title Screen (use Cloud Client's title screen, yes/no)

- **Q: Can this mod/feature be added?**  
Remember that you can add mods yourself, since Cloud Client is a Forge mod. duplicat does add mods to the client itself, in some updates. You can, however, go to the official Discord server and make suggestions on the `#┃suggestions` channel. Make sure the suggestion hasn't been made yet! 

- **Q: Why isn't Cloud Client getting updates!?**  
Cloud Client doesn't automatically download and install updates, if that's what you mean, so check every now and then. duplicat makes announcements in the Discord every time there's an update. If there's a lack of updates for a while, remember that duplicat might be doing stuff behind the scenes. Any changes that are committed to the development branch of the GitHub repo will be available for everyone. You can build the client yourself and get early access to features, and maybe even help debug the update (instructions on the official repo). Please don't go and rush duplicat, he's the only developer (there are a few contributors, but they're not active anymore), and he has his own life, like all of us do.

- **Q: Is Cloud Client available for Minecraft versions after 1.9?**  
Yes, 1.12.2 is supported, but modern versions of Minecraft like 1.16.x and later aren't supported **yet.** but again, don't go and rush duplicat, remember that modern Minecraft greatly differ from 1.12.2 (they're basically a different game), and that managing many versions of the mod is hard.

- Q: **I found a bug! What do I do?**  
Report it! First, remember to **check** if the bug you found is known, or fixed in a later update than when you found it. The most reliable ways of knowing are the [issue tracker](https://github.com/CloudClientDev/cloudclient/issues) (by extension, the repo itself) and the [official Discord server](https://discord.gg/uYPf2XvR) (channels: `#┃support, #┃bug-reports`, `#┃github`, `#┃changelog`, `#┃announcements`). I also have an unofficial [known bugs list](https://github.com/JuxGD/cloudclient-faq/tree/main/BUGS.md) in this repo. The preferred way to report bugs and glitches is to open an issue on the issue tracker. For a more direct way to report bugs, you can join the Discord. Remember to read `#┃rules` and `#┃faq` before anything. *also don't ping duplicat*

  ###### psst you can find me there too! Jux#2213

- **Q: I found a modpack that includes it. Is it official?**  
Chances are, it's my modpack, [The Cloud Client Experience](https://modrinth.com/the-cloudclient-experience)! No, it's not official, but duplicat gave me permission to upload it to Modrinth, if I followed some conditions (which I did). At the moment, there are no official modpacks.

  ###### shameless plug, also DUPLICAT MAKE IT OFFICIAL PLEASE I'LL DO ANYTHING

- **Q: So then, can I make a modpack including Cloud Client?**   
I'd say yes if you follow his conditions, go ask duplicat just in case, but *don't ping him. I am watching =D*
  ###### jk, don't ping duplicat tho
When I asked duplicat if I could put my modpack on modrinth, he said that as long as I don't claim Cloud Client to be my own mod, I give clear credit, and don't make money, it would be okay. So, naturally, it would be reasonable to assume that if you follow those same conditions, you won't be in any trouble.

- **Q: `#┃faq` in the Cloud Client discord server says that the client is licensed under GPLv3!**  
That FAQ is very outdated. At the time it was written, the client wasn't even public, and a lot has changed since then (that's why I'm making this one). On the Cloud Client repo, the license is currently LGPLv3.

- **Q: Will the rewrite be open source?**  
duplicat hasn't made a statement on what the rewrite's source model will be. It'd be reasonable to assume that it'll be open source, however, nothing's known for sure until duplicat says something about it.

- **Q: Does duplicat do partnerships for Cloud Client?**  
No, and it's not planned.

- **Q: Does Cloud Client have cosmetics?**  
No, but there are other mods that add them.

- **Q: Something's missing / There's a mistake. Can I contribute to the FAQ or the known bugs list?**  
[Yes!](https://github.com/JuxGD/cloudclient-faq/tree/main/CONTRUBUTING.MD)

## License/Copying
This repository is distributed under the terms of the [replicense](https://github.com/JuxGD/replicense) (rpli).
