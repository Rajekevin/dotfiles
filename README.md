# Manjaro : virtualbox full screen


Start by updating and upgrading all packages installed in the system.

sudo pacman -Syu

After the upgrade is done, reboot your machine.

sudo reboot

Then install virtualbox-guest-utils package.

$ sudo pacman -Sy virtualbox-guest-utils
:: Synchronizing package databases...
 core is up to date
 extra is up to date
 community is up to date
 multilib is up to date
warning: virtualbox-guest-utils-6.1.8-2 is up to date -- reinstalling
resolving dependencies...
looking for conflicting packages...

Packages (1) virtualbox-guest-utils-6.1.8-2

Total Installed Size:  7.26 MiB
Net Upgrade Size:      0.00 MiB

:: Proceed with installation? [Y/n] y

Reboot your machine.

sudo systemctl reboot
