# TeamSpeak 3 Server List Emulator
The TS3 Weblist Emulator was written in Java 8, it was created by Kaptan647 for R4P3.NET

## How to install Java 8 on Ubuntu
> Note: These are unofficial packages.
``` console
echo "deb http://ppa.launchpad.net/webupd8team/java/ubuntu xenial main" | tee /etc/apt/sources.list.d/webupd8team-java.list
echo "deb-src http://ppa.launchpad.net/webupd8team/java/ubuntu xenial main" | tee -a /etc/apt/sources.list.d/webupd8team-java.list
apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys EEA14886
apt-get update
apt-get install oracle-java8-installer
```

## How to run it
First, you have to download these files!
Visit for that, [the releases page.](https://github.com/SossenSystems/TS3-ServerListEmulator/releases "The GitHub releases page from SossenSystems")

#### For Linux
``` console
apt-get install curl
apt-get install unzip
curl -LO https://github.com/SossenSystems/TS3-ServerListEmulator/releases/download/v.1.2/ServerEmulatorPack.zip
unzip ServerEmulatorPack.zip
chmod 777 Weblist-Emulator/*
rm ServerEmulatorPack.zip
```
#### Open the console
``` console
java -jar ServerListEmulatorv3.jar "String of the Server Name" {PORT} {SLOTS} {RANDOM MIN USER} {RANDOM MAX USER}
```
##### If you do so a return code get's then you have done everything right:
``` console
root@WeblistStar:/home/SLE+FloodScript# java -jar ServerListEmulatorv3.jar "[PUBLIC] TS3Public.de - Community Server" 1337 1024 120 256
Welcome to the Teamspeak 3 Serverlist emulator
It made by me: Kaptan647 for r4p3.net Enjoy!
Serverlist-Emulator: Successfully added server '[PUBLIC] TS3Public.de - Community Server' to on port 1337 with 1024 slots and 140 clients to serverlist
```

P.S.: The `runSLE-flood.sh` script was only scripted for Linux users, tested on Ubuntu 16.04.

## What's next?
That's on to do:
+ The improved version of the C# SL-Emulator __[by Bluscream](https://github.com/Bluscream/TS3SRV-SLE)__
  - A small detail, about this:
    + Added multi entries to the weblist

Have fun to flood the TeamSpeak 3 server list :laughing:

# Badges
[![forthebadge](https://forthebadge.com/images/badges/made-with-java.svg)](http://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)
