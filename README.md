# Heart Strike
This is a (mostly) open source skripting project for Minecraft. This is an RPG server which can be self-hosted although there are official instances of the server you may check out. When the server is more fleshed out, I will include more details of the gameplay, it is planned to be a fully functional RPG.

There are many benifits to making a Minecraft server open source:
1. People can look at the source code to learn how the server functions and help to find and fix bugs or suggest cleaner code.
2. You can play on a private instance and modify your version of server files as you wish.
3. The server, or game, is preserved for longer if the official instances shut down.

# How to Play / Create Your Own Instance
Here are the steps to create and join your own instance of Heart Strike:
1. Downloading the files:
    1. A version of Paper for Minecraft 1.20.4 and rename the file to "Paper.jar".
    2. The following plugins from the internet, __it does not need to be the exact version__ and the format goes as following, PLUGIN (`VERSION USED DURING DEVELOPMENT`):
        - Freedom Chat (`1.5.2`)
        - Via Version (`4.9.2`)
        - Via Backwards (`4.9.1`)
        - Fast Async World Edit (`2.8.5-SNAPSHOT-646`)
        - World Guard (`7.0.9`)
        - Skript (`2.8.2`)
        - SkBee (`3.3.0`)
        - DiSky (`4.12.2-beta1`)
        - Skript Particle (`1.2.0`)
        - Diskuise (`0.3.4`)
        - ProtocolLib (`5.1.0`)
        - Libs Disguises (`10.0.41-Free`)
        - Citizens (`2.0.33-b3305`)
        - Mythic Mobs (`5.5.1`)
        - Mythic Skript Addon (`0.99.4`)
    3. Next, here on GitHub at the top of the page click `Code` > `Download ZIP`
    4. Download the world file from Mega __https://mega.nz/file/wjcWUBZQ#HOGV5RQ72fgFK7v4rxCvpaYn8HkmYBr1n93piov-Pco__
2. Setting up a Minecraft server:
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

## Special Thanks To...
- Raspi_Dude, for providing a host to one of the instances (24/02/2024-Present). 

- FOSS developers across the board and around the world. I'm so glad you all exist.

- Grass, I touched it one time and it was nice.
