Borrie's SWG Launcher
Version 2.0

DESCRIPTION:
This launcher is designed to prove a very quick and accessible way for new servers to provide their new players with a way of downloading their files, syncing their clients, and opening up the possibility of furthering their development goals with an effective updater and file verification system. Inspired by the Launcher built for Relics of Corbantis by Progor, this launcher will verify each file by checking their MD5 Checksum. To reduce the time it takes for an update, the administrator can flag certain files to be checked for updates. 

HOW IT WORKS: 
You distribute the launcher to your players with a customized config.ini file that has assigned a URL to a Manifest XML File which contains all the pertinent data required for your server. You can also provide a URL for your server's website and discord, as well as give the launcher a custom name. 

The end user will then start the launcher, which will download and read the manifest file. This manifest file will make sure that the user has all required files, and that the files are validated. To reduce the amount of files that you need to host, and to reduce download times, the launcher will automatically create and update the appropriate login and live config files with the provided information, allowing you to dynamically change the load order of TRE files, and your IP without the user needing to download anything new. All files are downloaded into the "Client" folder 

The Launcher also comes with the ability to download and install several mods, as well as modify the game's RAM maximum usage and framerate. In addition to this, a profile manager is included which allows you to peruse through your profiles and copy keymap configurations to different characters. This makes it easier to store and load custom keymaps for those who are not satisfied with the game's default keybindings. Last but not least, this profile feature allows the launcher to know which accounts have been logged into the game and allow you to preset the username on the game to one of your accounts. 

Last but not least, the launcher comes with an optional button that launches Utinni, a plugin framework developed by ModTheGalaxy's Timbab, which offers plugins such as The Jawa Toolset which can do detailed snapshot editing, as well as a few plugins made by Borrie. 

UNDERSTANDING THE MANIFEST:
The Manifest file is a simple XML file with three categories to keep in mind. The files, TRE Order, and Server Info. The files each have a node called "File" which denotes the name of the file, whether or not it will be checked when looking for updates (handy for frequently updated files, and files that are never updated, for speed), the checksum of the correct file, and the URL of the file for it to download. Check the MD5 Checksum of your files and update each one accordingly. By default, The Manifest file is set up to download MTG TRE Files, however you will need to provide the hosting for these files yourself. Commonly shared file types such as DLLs are provided by SWGEmu's website by default. 

The TRE Order allows you to set the order of TRE files that will be loaded. These settings will automatically generate the configuration files.

Server Info will dynamically update the client to connect to the given IP and port of your server, ensuring you can update your player's clients quickly with the most recent and accurate connection information. 

NOTE: This launcher requires an established client already installed that was installed with the genuine Star Wars Galaxies disks in order to adhere to SWGEmu's licensing agreements. Additionally, due to the nature of this program, anti-virus programs may flag this software as malicious, due to the fact that it downloads files to your machine. These flags are erronous, though when downloading files from a server you do not trust, use caution.

CREDITS:
Borrie BoBaka
SPECIAL THANKS:
Progor
Timbab

LINKS:
Find other cool mods at Mod the Galaxy!
https://www.modthegalaxy.com