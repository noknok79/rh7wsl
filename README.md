#Red Hat Enterprise Linux UBI 7 for WSL2

The file is above 25MB, so i have to upload the file to my google cloud. use 7z to extract the file which is nearly 1.5GB tar.gz https://drive.google.com/file/d/1-LY_lPQZiH0u_Ugx1EDFkzKuUPDUJy42/view?usp=sharing

Just simple import to wsl using command wsl --import <name_for_this_distro> <local_directory> <this_package> --version 2

then run using the command wsl -d <name_for_this_ditro>

then try to execute systemctl status.
