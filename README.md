# LoE Realm NC 2
LoE Realm New Chicago 2 version source code project.

# How to setup this source?
- https://youtu.be/86m6G74H_jU 
(or read below)
## Client
- Go to this file client\src\com\company\assembleegameclient\parameters\Parameters.as;
- Change value of variable IS_DEVELOPER_MODE to false;
- Go to this variable, at same file, ENVIRONMENT_DNS and change value of testing.loesoftgames.ignorelist.com to your IP or DNS;
- Build your client, it'll be compiled at client\client\client-release.swf.
## Server
- Go to this file server\common\config\Settings.cs;
- Change value of variable SERVER_MODE to ServerMode.Production;
- Go to this variable, at same file, ALLOWED_LOCAL_DNS and change value of testing.loesoftgames.ignorelist.com to your IP or DNS;
- Go to this file server\common\config\internal\Networking.cs;
- Go to this variable PRODUCTION_DDNS and change value of testing.loesoftgames.ignorelist.com to your IP or DNS;
- Go to this variable CROSS_DOMAIN_POLICY and change occurrencies of testing.loesoftgames.ignorelist.com to your IP or DNS;
- Build your server, then to run it go to server folder and open in order _storage_engine.bat then _initialize_game.bat.
(Did this in case the LoE Realm NC 1 thingy gets deleted)

# Discord:
- [![Join Us!](https://discordapp.com/api/guilds/345060662260531202/embed.png)](https://discord.gg/htpVTFq)

# AppEngine (read-only) Repository for remote data:
- https://loesoft-games.github.io/

# Requirements:

## Microsoft Visual Studio
Download the Microsoft Visual Studio IDE to compile game server, link below:
- https://www.visualstudio.com/downloads/

## Adobe Flex SDK 4.9.1
Download the properly Adobe Flex SDK to compile game client, link below:
- https://drive.google.com/uc?id=0B9pmoNsaxaKxQlh6MloycXZKazQ&export=download

## IntelliJ Idea Ultimate (or some other)
Download the IntelliJ Idea Ultimate trial to compile client, link below:
- https://download.jetbrains.com/idea/ideaIU-2018.3.2.exe

### Last Loe Realm NC 2 build before it got private. (version 2.3) If you want the '2.4 build', there is a different branch and you can merge that into the main branch/use the '2.4 branch'.
