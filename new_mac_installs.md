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
* Apple's X11.app is provided by the "X11 User" package on older OS versions. It is always installed on Lion, and is an optional installation on your system CDs/DVD with previous OS versions.

# MacPorts
 - [x] Put details in here how to install MacPorts
 
Download latest package (.pkg) file from https://github.com/macports/macports-base/releases/ and install it.
Check it's working from command line by running `port version`

Consider putting `sudo port selfupdate` in sheduler/cron to keep everyting up to date, and `sudo port reclaim` to reclaim space by uninstalling inactive ports, and removing unnecessary files that were downloaded during the installation process.

# Security
| Name        | Use                 | Location                                                        |
|-------------|---------------------|-----------------------------------------------------------------|
| Malwarebyts | Anti-Adware/malware | https://www.bleepingcomputer.com/download/malwarebytes-for-mac/ |

# Utilities

| Name               | Use                                                                                                           | Location                                                                                              |
|--------------------|---------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| Alfred             |                                                                                                               | https://www.alfredapp.com/ & add-ons https://pacmax.org/                                              |
| AppCleaner         | Remove the left overs when you uninstall an app                                                               | http://freemacsoft.net/appcleaner/                                                                    |
| AppPolice          | MacOS app for quickly limiting CPU usage by running applications                                              | https://github.com/AppPolice/AppPolice/releases                                                       |
| Bluetooth Keyboard |                                                                                                               | https://bluetooth-keyboard.com/                                                                       |
| Calibre            | Manage e-book collections as well as create, edit, and read e-books                                           | http://calibre-ebook.com/                                                                             |
| ClipMenu           | Clipboard manager that stores 100 items or more                                                               | http://www.clipmenu.com/                                                                              |
| Cot Editor         | Light weight text editor                                                                                      | https://coteditor.com/                                                                                |
| Darktable          | Virtual lighttable and darkroom                                                                               | https://www.darktable.org/install/                                                                    |
| Gas Mask           | Hosts file editor                                                                                             | https://github.com/2ndalpha/gasmask/releases                                                          |
| Glance             | Quick Look previews for files that macOS doesn't support out of the box                                       | https://apps.apple.com/us/app/glance-quick-look-plugin/id1513574319                                   |
| HomeBrew           | Package manager                                                                                               | https://brew.sh/                                                                                      |
| iTerm 2            | Terminal replacement - including split pains                                                                  | https://www.iterm2.com/                                                                               |
| Knock Knock        | See what's persistently installed on your Mac                                                                 | https://www.objective-see.com/products/knockknock.html                                                |
| Latest             | A small utility app that makes sure you know about all the latest updates to the apps you use                 | https://github.com/mangerlahn/Latest/releases                                                         |
| LaunchRocket       | PrefPane to manage all your Homebrew-installed services                                                       | https://github.com/jimbojsb/launchrocket/releases                                                     |
| Light Table        | Code Editor                                                                                                   | http://lighttable.com/                                                                                |
| Little Sitch       |                                                                                                               |                                                                                                       |
| MenuBar Stats 3    |                                                                                                               | https://www.seense.com/menubarstats/ & https://www.seense.com/menubarstats/plugins3/ (Plugin manager) |
| NetNewsWire        | RSS Reader                                                                                                    | https://ranchero.com/netnewswire/                                                                     |
| OnyX               |                                                                                                               | https://www.titanium-software.fr/en/onyx.html                                                         |
| Office 365         | The defacto business apps suite                                                                               | https://www.microsoft.com/en-gb/microsoft-365/buy/compare-all-microsoft-365-products                  |
| PlayStatus         | App that allows the control of Spotify and iTunes music playback from the menu bar                            | https://github.com/nbolar/PlayStatus/releases                                                         |
| Rates              | Currency Conversion App                                                                                       | https://github.com/nbolar/Rates/releases                                                              |
| Sublime Text       | A sophisticated text editor for code, markup and prose                                                        | https://www.sublimetext.com/                                                                          |
| Syncthing          | Synchronise file across multiple sites and o/s's                                                              | https://syncthing.net/                                                                                |
| Trailer            | Track pull requests and issues across git repositories, directly in your Notification Center or on any device | http://ptsochantaris.github.io/trailer/                                                               |
| Visual Studio Code | Source code editor                                                                                            | https://visualstudio.microsoft.com/vs/mac/                                                            |

# GIT
| Name                | Use                 | Location                                          |
|---------------------|---------------------|---------------------------------------------------|
| Auto sync GIT repos | Auto sync GIT repos | https://thedoc.eu.org/blog/auto-sync-git-repo-mac |
| Sublime Merge       | Git Client          | https://www.sublimemerge.com/                     |

# Fun Stuff

## Screensavers :
* Aerial : https://github.com/JohnCoates/Aerial
* MusaicFM : https://github.com/docterd/MusaicFM/releases/latest/download/MusaicFM.saver.zip

# Stuff to play with when I have time

| Name         | Use                                                                        | Location               |
|--------------|----------------------------------------------------------------------------|------------------------|
| Ardour       | Record, Edit, and Mix on Linux, macOS and Windows                          | https://ardour.org/    |
| Hombridge.io | Integrate with smart home devices that do not support the HomeKit protocol | https://homebridge.io/ |
