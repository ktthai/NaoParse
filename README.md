# Nao Parse
 Nao Parse is a small and simple damage parser that was written based on [MabiPale2](https://github.com/exectails/MabiPale2). To use this you need a proxy to intercept the packets sent to and from Mabinogi. I suggest using [Morrighan](https://github.com/exectails/Morrighan).

## Installation and usage
For the installation and usage process we are going to be using Morrighan. You can read about how to connect to Morrighan [here](https://github.com/exectails/Morrighan/blob/master/README.md#how-to-connect-to-morrighan), but I will also write a short version of that.  

1. Grab the latest Morrighan release [here](https://github.com/exectails/Morrighan/releases), and place it on your Mabinogi folder, usually `C:\Nexon\Library\mabinogi\appdata`.
2. From here, you can choose the way you would like to launch the game with Morrighan. If you would like to use the nexon launcher, make a .bat in the same folder with `Morrighan.exe code:1622 verstr:248 ver:248 locale:USA env:Regular setting:file://data/features.xml logip:35.162.171.43 logport:11000 chatip:54.214.176.167 chatport:8002 nxlauncher` and use that. Otherwise, you can use anything that is able to edit the command line options to Client.exe. For example, if you wish to launch the game via [Kanan Launcher](https://github.com/cursey/kanan-new), all you would need to do click Customize Command Line, and set it to this `C:\Nexon\Library\mabinogi\appdata\Morrighan.exe code:1622 verstr:248 ver:248 locale:USA env:Regular setting:file://data/features.xml logip:35.162.171.43 logport:11000 chatip:54.214.176.167 chatport:8002`. Keep in mind of the folder path, if you have a different one.
3. From the moment the Mabinogi Client is launched, and Morrighan is running, you can launch Nao Parse.exe.  
  
## FAQ/Notes
If you launch Nao Parse.exe after your character has already the channel, you will need to Change Channel once, for the parser to be able to save your character name, as well as the name of the characters already around you.

**I did everything right, but no damage is coming through**  
I suggest launching Nao Parse as admin.

**I got an error whilst it was parsing**  
Please create an Issue for it, preferrably with a description of what caused it(in game), and I will attempt to fix it.

**How do I use this with a VPN or Ping Booster?**  
You have to set the vpn/ping booster to Morrighan.exe instead of Client.exe.
