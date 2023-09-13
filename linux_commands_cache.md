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
