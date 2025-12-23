

Intended for my self usage for not dealing with the long process of gentoo installation, though written around bash as thats the default shell in gentoo installer.
What its not : Its not an interactive installer that gives options for choosing init system , complex filesystem setup like zfs that requires importing modules outside the linux kernel,option to choose from open-rc or systemd.

ToDo after installation : This script assumes my system configs from the disk like nvme express to processor, therefore the use flags needs to be tweaked, even the default profiles, and if required the cflags and rust flag setup after a bare working system state is acheived.
Therefore approprate changes are to be made, system wide or per package in /etc . Thus it requres rebuilding of @world again !



I further plan to include pipewire setup and sway-wm (pure wayland only) sometime,along with nix install and its required creation of builder groups. 
