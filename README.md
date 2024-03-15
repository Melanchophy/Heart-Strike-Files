# Heart Strike
This is a (mostly) open source skripting project for Minecraft. This is an RPG server which can be self-hosted although there are official instances of the server you may check out. When the server is more fleshed out, I will include more details of the gameplay, it is planned to be a fully functional RPG.

There are many benifits to making a Minecraft server open source:
1. People can look at the source code to learn how the server functions and help to find and fix bugs or suggest cleaner code.
2. You can play on a private instance and modify your version of server files as you wish.
3. The server, or game, is preserved for longer if the official instances shut down.

![Image](/YouMayNotNeedThis/Heart%20Strike.webp)

## Contact Me/The Community
If you are interested in the project or would like to get in touch, you can message or join me on Discord, my username is `Melanchophy` (Pronounced "Melan Coffee") and the invitation link to my Discord server is here:

[__💙 Parliament of Owls 💙__](https://discord.gg/fQUzhGpf3a)

[![Image](/YouMayNotNeedThis/Parliment%20of%20Owls.webp)](https://discord.gg/fQUzhGpf3a)

# How to Play / Create Your Own Instance
Here are the steps to create and join your own instance of Heart Strike. Remember to keep calm during each process:
1. Downloading the following files:
    1. A version of [Paper for Minecraft 1.20.4](https://papermc.io/downloads/paper). Ensure the file name is set to "Paper.jar"!
    2. The following plugins from the internet, __it does not need to be the exact version__ and the format goes as following, "PLUGIN, (`VERSION USED DURING DEVELOPMENT`)":
        - [Freedom Chat](https://modrinth.com/plugin/freedomchat) (`1.5.2`)
        - [Via Version](https://github.com/ViaVersion/ViaVersion/releases) (`4.9.3`)
        - [Fast Async World Edit](https://ci.athion.net/job/FastAsyncWorldEdit/) (`2.9.1-SNAPSHOT-674`)
        - [World Guard](https://dev.bukkit.org/projects/worldguard) (`7.0.9`)
        - [Skript](https://github.com/SkriptLang/Skript/releases) (`2.8.3`)
        - [SkBee](https://github.com/ShaneBeee/SkBee/releases/) (`3.4.1`)
        - [DiSky](https://modrinth.com/plugin/disky/version/3utXU8e8) (`4.12.2-beta1`)
        - [Skript Particle](https://github.com/sovdeeth/skript-particle/releases) (`1.2.0`)
        - [Diskuise](https://github.com/UnderscoreTud/diskuise/releases) (`0.3.4`)
        - [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) (`5.1.0`)
        - [Libs Disguises](https://github.com/libraryaddict/LibsDisguises/releases) (`10.0.42-Free`)
        - [Citizens](https://ci.citizensnpcs.co/job/Citizens2/) (`2.0.33-b3365`)
        - [Mythic Mobs](https://mythiccraft.io/index.php?resources/mythicmobs.1/) (`5.6.1`)
        - [Mythic Skript Addon](https://github.com/BerndiVader/MythicSkriptAddon/releases) (`0.99.6`)
    3. Next, here on GitHub at the top of the page click `Code` > `Download ZIP`
    4. Download the world file, __https://mega.nz/file/wjcWUBZQ#HOGV5RQ72fgFK7v4rxCvpaYn8HkmYBr1n93piov-Pco__
        (I'm not sure if I should host the file here on GitHub...)
2. Setting up a 1.20.4 Paper server:
    1. Create a new folder at location of your choice, for example `/home/USER/Heart Strike/`.
    2. Move all of the downloaded files into the folder you created.
    3. Open the Terminal/Powershell application and execute the commands in order:
        - cd Path/To/Server/
        - java -Xmx2G -Xms2G -jar paper.jar --nogui
    4. The server will not start, that is normal, it should make a file named "Eula". Open it and agree (replace the only "False" with "True").
    5. Follow step `2-3` again.
    6. Close the server by closing the Terminal/Powershell or by entering `stop`.
3. Setting up Heart Strike:
    1. Paste the plugins from `1-2` into the `*/plugins/` folder created by the server.
    2. Move then unzip the ZIP file from `1-3` into `*/plugins/` too. 
    3. Unzip the world download file from Mega directly into the server's folder `*/`.
    4. Follow step `2-3` again. The server should be online and you can join it in game using the IP address `0`.

# How to Update
Here are the steps on updating the server if you already have one up and running:
1. Download the latest world file (I will include version names so you can check if you have the most up-to-date file already).
    - Unzip the world file in `*/` and replace the old world.
2. At the top of this page click `Code` > `Download ZIP`
    - Unzip the ZIP file in `*/plugins/` and replace the old files.

# Special Thanks To...
Raspi_Dude, for providing a host to one of the instances (24/02/2024-Present). 

![Image](/YouMayNotNeedThis/Raspi%20Dude.webp)

FOSS developers across the board and around the world. I'm so glad you all exist.

![Image](/YouMayNotNeedThis/LineageOSmyBeloved.png)

Grass, I touched it one time and it was nice.

![Image](/YouMayNotNeedThis/Grass.jpeg)
