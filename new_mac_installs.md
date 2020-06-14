# Xcode (Required for many others, e.g. MacPorts)
Apple's Xcode Developer Tools can be found at the Apple Developer site, on your Mac operating system installation CDs/DVD, or in the Mac App Store. Using the latest available version that will run on your OS is highly recommended, except for Snow Leopard where the last free version, 3.2.6, is recommended.
* 11.0 or later for Catalina
* 10.0 or later for Mojave
* 9.0 or later for High Sierra
* 8.0 or later for Sierra
* 7.0 or later for El Capitan
* 6.1 or later for Yosemite
* 5.0.1 or later for Mavericks
* 4.4 or later for Mountain Lion,
* 4.1 or later for Lion
* 3.2 or later for Snow Leopard
* 3.1 or later for Leopard

Apple's Command Line Developer Tools can be installed on recent OS versions by running this command in the Terminal:

```bash
xcode-select --install
```
Older versions are found at the Apple Developer site, or they can be installed from within Xcode back to version 4.

Users of Xcode 3 or earlier can install them by ensuring that the appropriate option(s) are selected at the time of Xcode's install ("UNIX Development", "System Tools", "Command Line Tools", or "Command Line Support").

Xcode 4 and later users need to first accept the Xcode EULA by either launching Xcode or running:

```bash
xcodebuild -license
```

(Optional) The X11 windowing environment for ports that depend on the functionality it provides to run. 
You have multiple choices for an X11 server:
* Install the xorg-server port from MacPorts (recommended).
  * - [x] Put details in here how to install
* The XQuartz Project provides a complete X11 release for macOS including server and client libraries and applications. It has however not been updated since 2016.
* Apple's X11.app is provided by the “X11 User” package on older OS versions. It is always installed on Lion, and is an optional installation on your system CDs/DVD with previous OS versions.

# MacPorts
 - [x] Put details in here how to install MacPorts
 
Download latest package (.pkg) file from https://github.com/macports/macports-base/releases/ and install it.
Check it's working from command line by running `port version`

Consider putting `sudo port selfupdate` in sheduler/cron to keep everyting up to date, and `sudo port reclaim` to reclaim space by uninstalling inactive ports, and removing unnecessary files that were downloaded during the installation process.

# Utilities

Name         | Use           | Location
------------ | ------------- | -------------
AppCleaner   | Remove the left overs when you uninstall an app | http://freemacsoft.net/appcleaner/
Bluetooth Keyboard | | https://bluetooth-keyboard.com/
Knock Knock | See what's persistently installed on your Mac | https://www.objective-see.com/products/knockknock.html
Little Sitch | | 
MenuBar Stats 3 | | https://www.seense.com/menubarstats/ & https://www.seense.com/menubarstats/plugins3/ (Plugin manager)
OnyX |  | https://www.titanium-software.fr/en/onyx.html
Syncthing | Synchronise file across multiple sites and o/s's | https://syncthing.net/

# GIT
Name         | Use           | Location
------------ | ------------- | -------------
Auto sync GIT repos | Auto sync GIT repos | https://thedoc.eu.org/blog/auto-sync-git-repo-mac

# Fun Stuff

## Screensavers :
* Aerial : https://github.com/JohnCoates/Aerial
* MusaicFM : https://github.com/docterd/MusaicFM/releases/latest/download/MusaicFM.saver.zip

# Stuff to play with when I have time

Name         | Use           | Location
------------ | ------------- | -------------
Ardour | Record, Edit, and Mix on Linux, macOS and Windows | https://ardour.org/
