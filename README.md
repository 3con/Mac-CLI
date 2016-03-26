# mac
The ultimate tool to manage your Mac. It provides a huge set of command line commands that automatize the usage of your OS X system.
When you run a function, the executed command is displayed and that helps you memorize each of the utilities for future usage.

# Configuration
Update the shell script to match your local environment configuration. Global variables are defined at the beginning of the file.

# Requirements
These are the requirements to be able to run all the commands:

* Git
* Pipe Viewer (pv)

### Commands List

| Command  | Description | Arguments |
| ------------- | ------------- | ------------- |
| `mac list`  | List all available commands in mac script  | |
| `mac list:general`  | List all general commands in mac script  | |
| `mac list:search`  | List all search commands in mac script  | |
| `mac list:network`  | List all network commands in mac script  | |
| `mac list:lamp`  | List all LAMP commands in mac script  | |
| `mac list:performance`  | List all performance commands in mac script  | |
| `mac list:terminal`  | List all terminal commands in mac script  | |
| `mac list:git`  | List all GIT commands in mac script  | |
| `mac list:web`  | List all Web commands in mac script  | |
| `mac list:brew`  | List all Homebrew commands in mac script  | |
| `mac list:xcode`  | List all xCode commands in mac script  | |
| `mac list:magento`  | List all Magento commands in mac script  | |
| `mac list:apps`  | List all executable apps in mac script  | |

### General Commands

| Command  | Description | Arguments |
| ------------- | ------------- | ------------- |
| `mac update`  | Install OS X software updates, update installed Ruby gems, Homebrew, npm and their installed packages  | |
| `mac restart`  | Restart OS X  | |
| `mac sleep`  | Sleep mode  | |
| `mac shutdown`  | Shutdown  | |
| `mac screensaver`  | Start screensaver  | |
| `mac folders:list`  | List folders in current directory  | |
| `mac folder:size`  | Calculate current folder size  | |
| `mac folders:remove-empty`  | Remove empty subdirectories  | |
| `mac apps:close-all`  | Close all opened apps  | |
| `mac apps:app-store`  | Get list of installed apps from App Store  | |
| `mac eject-all`  | Eject all mounted volumes and disks  | |
| `mac battery:info`  | Get battery information  | |
| `mac info`  | Get OS X version information  | |
| `mac find:text X`  | Find exact phrase recursively inside directory  | X = Text string |
| `mac zip:extract X` | Extract Zip file to current folder | X = Zip file to extract |
| `mac gzip:compress X` | Compress current file using Gzip | X = File to compress |
| `mac gzip:extract X` | Extract Gzip file to current folder | X = Gzip file to extract |
| `mac tar:compress X`  | Compress X file/directory using tar with progress indicator  | X = File or directory |
| `mac tar:extract X` | Extract tar file to current folder | X = Tar file to extract |


### Search Utilities

| Command  | Description | Arguments |
| ------------- | ------------- | ------------- |
| `mac find:recent N`  | Find files modified in the last N minutes  |  N = number of minutes  |
| `mac search:replace X` | Search and replace string in file | X = File to perform the search and replace operation |


### Network Utilities

| Command  | Description |
| ------------- | ------------- |
| `mac speedtest`  | Internet connection speed test  |
| `mac speedtest:infinite`  | Run internet speed test each 5 minutes  |
| `mac ports`  | List of used ports  |
| `mac ip:local`  | Get local IP address  |
| `mac ip:public`  | Get public IP address  |


### LAMP (Linux, Apache, MySQL, PHP)

| Command  | Description | Arguments |
| ------------- | ------------- | ------------- |
| `mac mysql`  | Open MySQL app (Rename SequelPRO.app to MySQL.app)  |  |
| `mac mysql-cli`  | Start MAMP MySQL CLI  |  |
| `mac phpmyadmin`  | Open PHPMyAdmin  | |
| `mac mysql:list`  | List all MySQL databases  | |
| `mac mysql:export-all`  | Export all MySQL databases to individual files  | |
| `mac mysql:dump X`  | Export MySQL database to current directory  |  X = database name  |
| `mac mysql:import X`  | Import MySQL database  |  X = SQL file  |
| `mac mysql:import-table X`  | Import single MySQL database table |  X = SQL file containing database table  |
| `mac mysql:create X`  | Create MySQL database  |  X = Database name |
| `mac mysql:drop X`  | Remove MySQL database  |  X = Database name |
| `mac mysql:duplicate X`  | Duplicate MySQL database  |  X = Database name |
| `mac mamp:start`  | Start MAMP Server (Apache and MySQL)  | |
| `mac mamp:stop`  | Stop MAMP Server (Apache and MySQL)  | |
| `mac mamp:restart`  | Restart MAMP Server (Apache and MySQL)  | |
| `mac ssh:download-file X`  | Download file from remote server through SSH  |  X = Path of the remote file to download  |
| `mac ssh:download-folder X`  | Download entire folder from remote server through SSH  |  X = Path of the remote folder to download  |
| `mac ssh:upload X`  | Upload file to remote server through SSH  |  X = Path of the file to upload to the remote server  |
| `mac php:syntax`  | Check PHP Syntax for all PHP files in current location  |  |
| `mac php:info`  | Get PHP info on command line  |  |
| `mac hosts:edit`  | Edit hosts file  |  |
| `mac ssh-key:copy`  | Copy SSH Public Key  |  |


### Performance and maintenance utilities

| Command  | Description |
| ------------- | ------------- |
| `mac memory`  | See memory usage sorted by memory consumption  |
| `mac trash:empty`  | Empty trash |
| `mac trash:size`  | Calculate trash size |


### iTerm / Terminal utilities

| Command  | Description |
| ------------- | ------------- |
| `mac iterm:tab-title`  | Set title to current iTerm tab  |


### GIT utilities

| Command  | Description |
| ------------- | ------------- |
| `mac git:config`  | Display local Git configuration  |
| `mac git:open`  | Open current repository on Github  |
| `mac git:create-branch`  | Create branch based on current branch  |
| `mac git:fresh`  | Get last update date for all branches in current project  |
| `mac git:undo-commit`  | Undo latest commit  |
| `mac git:log`  | See latest commits IDs and titles for current branch  |
| `mac git:branch`  | See all branches  |
| `mac git:remove`  | Remove GIT from current project  |
| `mac git:settings`  | Check GIT settings  |
| `mac git:open`  | Open current GIT repository URL  |

# Web utilities

| Command  | Description | Arguments |
| ------------- | ------------- | ------------- |
| `mac web:download-images`  | Download all images from website to current directory  |

### Homebrew utilities

| Command  | Description |
| ------------- | ------------- |
| `mac brew:list`  | Get list of installed Homebrew packages  |


### XCode utilities

| Command  | Description |
| ------------- | ------------- |
| `mac xcode:cleanup`  | Cleanup XCode files to free up hard disk space  |


### Magento utilities

| Command  | Description |
| ------------- | ------------- |
| `mac magento:version`  | Get Magento version from current project on command line  |


### Executable Apps

| Command  | Description |
| ------------- | ------------- |
| `mac firefox`  | Open Firefox  |
| `mac chrome`  | Open Chrome  |
| `mac safari`  | Open Safari  |
| `mac phpstorm`  | Open PHPStorm  |
| `mac mamp`  | Open MAMP  |
| `mac filezilla`  | Open Filezilla  |
| `mac gotomeeting`  | Open GoToMeeting  |
| `mac xcode`  | Open Xcode  |
| `mac snippetslab`  | Open SnippetsLab  |
| `mac preview`  | Open Preview  |
| `mac photoshop`  | Open Photoshop  |
| `mac skype`  | Open Skype  |
| `mac textedit`  | Open TextEdit  |
| `mac sourcetree`  | Open SourceTree  |
| `mac stree`  | Open current directory in SourceTree  |
| `mac quiver`  | Open Quiver  |
| `mac virtualbox`  | Open VirtualBox  |
| `mac pixelmator`  | Open Pixelmator  |
| `mac vlc`  | Open VLC  |
| `mac kaleidoscope`  | Open Kaleidoscope  |
| `mac mindnode`  | Open MindNode  |
| `mac paw`  | Open Paw  |
| `mac appstore`  | Open App Store  |
| `mac goodtask`  | Open GoodTask  |
| `mac notes`  | Open Notes  |