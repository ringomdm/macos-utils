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
- _kextstat_ - display status of loaded kernel extensions (kexts)
- _systemextensionsctl_ - System Extensions control
- _launchctl_ - Interfaces with launchd
- _launchd_ - System wide and per-user daemon/agent manager
- _com.apple.loginwindow.plist_
- _bputil_ - Utility to precisely modify the security settings on Apple Silicon Macs
- _bless_ - set volume bootability and startup disk options
- _plutil_ - property list utility
- _PlistBuddy_ - read and write values to plists
## Network 
- _ifconfig_ - configure network interface parameters
- _hostname_ - set or print name of current host system
- _networksetup_ - configuration tool for network settings in System Preferences
- _scselect_ - Select system configuration "location"
- _kickstart_
- _wdutil_ - Wireless Diagnostics command line utility
- _airport_ - [deprecated]
- _sysctl_ - get or set kernel state
- _route_ - manually manipulate the routing tables
- _netstat_ - show network status
- _ipconfig_ - view and control IP configuration state
- _traceroute_ - print the route packets take to network host
- _nc_ - arbitrary TCP and UDP connections and listens
- _tcpdump_ - dump traffic on a network
- _socketfilterfw_ - Application Firewall daemon
- _networkQuality_ - Network quality testing tool
## Samba
- _smbutil_ - interface to the SMB requester
- _nsmb.conf_ - configuration file for SMB requests
## Printers
- _lpadmin_ - configure cups printers and classes
## Power settings
- _pmset_ - manipulate power management settings
- _caffeinate_ - prevent the system from sleeping on behalf of a utility
- _.GlobalPreferences.plist_
- _powermetrics_
## Users
- _com.apple.loginwindow.plist_
- _chflags_ - change file flags
- _sc_auth_ - SmartCard authorization setup script
## Directory
- _dscl_ - Directory Service command line utility
- _dseditgroup_ - Manipulate group records with the Open Directory API
- _klist_ - list Kerberos credentials
- _app-sso_ - A tool used to control and get information about the Kerberos SSO extension
## MDM
- _profiles_ - Profiles Tool for macOS
- _mdmclient_ - MDM (Mobile Device Management) client
## Storage
- _diskutil_ - modify, verify and repair local disks
- _gpt_ - GUID partition table maintenance utility
- _fsck_apfs_ - APFS consistency check
- _fsck_ - filesystem consistency check and interactive repair
- _dd_ - convert and copy a file
- _mount_ - mount file systems
- _umount_ - unmount filesystems
## Spotlight
- _mdutil_ - manage the metadata stores used by Spotlight
## Time Machine
- _tmutil_ - Time Machine utility
## Software Intallation
- _pkgutil_ - Query and manipulate Mac OS X Installer packages and receipts
- _installer_ - system software and package installer tool
- _xattr_ - display and manipulate extended attributes
- _csrutil_ - Configure system security policies
- _spctl_ - SecAssessment system policy security
- _productbuild_ - Build a product archive for the macOS Installer or the Mac App Store
## Processes & Files
- _top_ - display sorted information about processes
- _ps_ - process status
- _kill_ - terminate or signal a process
- _killall_ - kill processes by name
- _log_ - Access system wide log messages created by os_log, os_trace and other logging systems
- _fs_usage_ - report system calls and page faults related to filesystem activity in real-time
- _dtruss_ - process syscall details. Uses DTrace
- _audit_ - audit management utility
