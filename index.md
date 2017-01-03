### Versions

Here you will find the latest modification of original **Transmission Remote GUI**. At the moment is the version 2017 year. 
[Download link...](https://github.com/leonsoft-kras/transmisson-remote-gui/releases/latest)

_The original version of the author (Yury Sidorov) - 2014 year, [Link...](https://sourceforge.net/projects/transgui/)_

### Features
* Native application for Windows, Linux and Mac OS X
* uTorrent-like interface
* Multilingual user interface
* Torrents filtering by status, tracker, folder
* Resolving of peer's host name and country
* Displaying of peer's country flag
* Tray icon and balloon tooltips when download is complete
* Association with .torrent files and magnet links
* Selectable download folder when adding a new torrent
* Select files to download
* Choose files and torrents priority
* View details about connected peers
* Full information about each torrent
* Per torrent options
* Trackers details 
* Rules to automatically suggest download directory

Transmission 1.40 or later is supported.

Transmission Remote GUI is developed using Lazarus RAD and Free Pascal compiler. 

![Window of TRG](http://s013.radikal.ru/i322/1503/8a/24bb45f03ffb.png)

### Command Line Parameters

You can specify path to a .torrent file or a magnet link as a command line parameter. The program will add the specified torrent.

`-hidden : Start the program hidden. Only the program's tray icon will be visible.`

`--home=<home_dir> : Specifies a home directory for the program. All program's settings are stored in the home directory. You can run multiple instances of the program by specifying different home directories.`

### Portable Mode

If the program finds the transgui.ini file in the same folder as the binary file, then it will store all configuration and data files in the program's folder, instead of the folder in a user profile.

### Advanced Parameters

There are some parameters in the tramsgui.ini file, that can not be modified via the GUI. 

