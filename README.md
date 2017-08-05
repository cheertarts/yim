# yam
Yam is the simplest aur helper ever made. It is 52 lines of source code. That is so short, that on a computer with no internet connection, you can hand type the entire source code in less than 5 minutes. Sadly the program is useless on a computer with no internet. It has three options:

    yam -d # -> downloads aur packages and their aur dependencies
    yam -u # -> downloads aur updates and notifies the user
    yam -s # -> searches the aur through aur names and descriptions

Yam requires bash, git, jshon, and curl.

# Why use this instead of cower?

Cower doesn't use git but tarballs, which has been deprecated since AUR 4. But also cower just has too many gosh dang features. It is 1000 lines of C code. Why? I rewrote the functionality I used in 52 lines. Plus it's also 3 letters instead of 5. If you're not convinced yet you're a lost cause.

# How do you download it?

    # Download yam's aur package with git
    git clone https://aur.archlinux.org/yam.git
    # Go into the yam directory
    cd yam
    # make the package
    makepkg -si
