# Linux Commands Cache

> #### **Arch linux specific commands (pacman)**

Update system: `sudo pacman -Syu`

List installed packages: `pacman -Q`

Search installed packages: `pacman -Qs <name>`

Search all packages: `pacman -Ss <name>`

Install package: `sudo pacman -S <name>`

Remove package, its dependencies, and config file backups: `sudo pacman -Rns <name>`

Clean old packages in cache: `pacman -Sc`

> #### Manual installation of AUR packages

1. Update repositories: `sudo pacman -Syu`
2. Grab the package: curl -0 `<package_url | https://aur.archlinux.org/packages/ya/yaourt/yaourt.tar.gz>`
3. Untar package: `tar xzvf <package.tar.gz>`
4. Change into package directory: `cd <package>`
5. Build and install: `makepkg -si`

> #### Arch linux specific commands (java environments)

Check status: `archlinux-java status`

Set default version: `archlinux-java set <version>`

> #### Basic must-know linux commands

Find path of current working directory: `pwd`

Change directory to home: `cd` or `cd ~`

Change directory one step back: `cd ..`

Change directory any particular location: `cd <path_of_the_location>`

List files and directories: `ls`, `ls -a`, `ls -R`

Copy file between locations: `cp <path_of_source_file> <path_of_destination_dir>`

Move file between locations: `mv <path_of_source_file> <path_of_destination_dir>`

Create new folder: `mkdir <directory_name>`

Delete file or directory: `rm -rf <file_or_folder_name>`

View your terminal commands history: `sudo history`
