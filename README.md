# macos-utils
## System Info
- sw_vers - print macOS system version information
- SystemVersion.plist
## macOS Install
- _softwareupdate_ - system software update tool
- /Applications/Install\ macOS\ Sonoma.app/Contents/Resources/
  - createinstallmedia - create macOS USB installer
  - startosinstall - install macOS - [Cheat Sheet](https://gist.github.com/acodega/57766c52a18a828b1ec44ad2492b5127)
## System Settings
- languagesetup - Set the primary language for the system
- cfprefsd - defaults server
- systemsetup - configuration tool for certain machine settings in System Preferences
- sysadminctl
- /Library/Preferences/.GlobalPreferences.plist
## Network Settings
- ifconfig - configure network interface parameters
- networksetup - configuration tool for network settings in System Preferences
## Printers
- lpadmin - configure cups printers and classes
## Power settings
- pmset - manipulate power management settings
- /Library/Preferences/.GlobalPreferences.plist
## Directory
dscl - Directory Service command line utility
dseditgroup - Manipulate group records with the Open Directory API
##
