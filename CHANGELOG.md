36.0.0
* Upgraded to Fedora 36

35.13.5
* Added SystemD optional support, adding an -s parameter to the fedoraremix.exe launcher.
* Added a new command wslsystemctl to start services without starting SystemD, as other distros like Ubuntu does with the service command.
* Added tweaks to be able to run snaps with WSLg.
* Added tweaks to be able to run GNOME Desktop using Remote Desktop Connection.

35.12.6
* Fix a launch error with Windows Terminal 1.12

35.12.5
* Added explicit error code and message for virtualization not present
* Improved the tiles in Start Menu in Windows 10 1809-1909

35.12.3
* Upgraded to Fedora 35
* Now the upgrade.sh script can be executed calling update.sh
* Fixed an error for some configurations that Fedora Remix cannot be executed from Windows Terminal
* Improved the logo in Windows 10 start menu
* Upgraded Mesa to 21.2.3, the latest version 21.3.1 provided by upstream Fedora 35 has a serious performance issue with GPU and WSLg

34.5.6
* Fixed a problem with dnf and WSL1
* Fixed a connection problem with XServer when fish is the default shell

34.5.5
* Automatically creates an entry with logo in Windows Terminal
* In App Settings, it is possible to set Fedora Remix launch at startup
* When a new distro is created, now the default user is written in wsl.conf. So, the default user is preserved on exports and imports
* For Windows Terminal add Fedora default color theme and background
* Fix a problem installing packages in WSL1
* Upgrade WSLU to 3.2.3
