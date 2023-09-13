# Linux Commands Cache

> #### **Arch linux specific commands (pacman)**

Update system: `sudo pacman -Syu`

List installed packages: `pacman -Q`

Search installed packages: `pacman -Qs <name>`

Search all packages: `pacman -Ss <name>`

Install package: `sudo pacman -S <name>`

Remove package, its dependencies, and config file backups: `sudo pacman -Rns <name>`

Clean old packages in cache: `pacman -Sc`
