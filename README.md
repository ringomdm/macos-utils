# macos-utils
## System Info
- _sw_vers_ - print macOS system version information
- _SystemVersion.plist_
## macOS Install
- _softwareupdate_ - system software update tool
- _/Applications/Install\ macOS\ Sonoma.app/Contents/Resources/_
  - _createinstallmedia_ - create macOS USB installer
  - _startosinstall_ - install macOS - [Cheat Sheet](https://gist.github.com/acodega/57766c52a18a828b1ec44ad2492b5127)
## System Settings
- _languagesetup_ - Set the primary language for the system
- _cfprefsd_ - defaults server
- _systemsetup_ - configuration tool for certain machine settings in System Preferences
- _sysadminctl_
- _.GlobalPreferences.plist_
- _fdesetup_ - FileVault configuration tool
- 
## Network Settings
- _ifconfig_ - configure network interface parameters
- _networksetup_ - configuration tool for network settings in System Preferences
- _kickstart_
## Printers
- _lpadmin_ - configure cups printers and classes
## Power settings
- _pmset_ - manipulate power management settings
- _.GlobalPreferences.plist_
## Users
- _com.apple.loginwindow.plist_
- _chflags_ - change file flags
## Directory
- _dscl_ - Directory Service command line utility
- _dseditgroup_ - Manipulate group records with the Open Directory API
## MDM
- _profiles_ - Profiles Tool for macOS
## Storage
- _diskutil_ - modify, verify and repair local disks
- _gpt_ - GUID partition table maintenance utility
- _fsck_apfs_ - APFS consistency check
- _fsck_ - filesystem consistency check and interactive repair
- _dd_ - convert and copy a file
## Spotlight
- _mdutil_ - manage the metadata stores used by Spotlight
## Time Machine
- _tmutil_ - Time Machine utility
## SIP (Monterey)
- /System
- /usr
- /bin
- /sbin
- /System/Volumes/Data/Applications/
- /private/var/db/ConfigurationProfiles
