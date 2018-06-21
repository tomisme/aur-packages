https://wiki.archlinux.org/index.php/Arch_Build_System
https://wiki.archlinux.org/index.php/Makepkg
https://www.archlinux.org/pacman/PKGBUILD.5.html

1. Update `PKGBUILD`
2. `updpkgsums`
3. `makepkg --printsrcinfo > .SRCINFO`
4. `makepkg -si`
5. Check it works!
6. `git push aur master`
