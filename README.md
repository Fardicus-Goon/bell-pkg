# bell-pkg
Bell-pkg is a shell based package management system that is designed to be simple! You can install a package by invoking [bell installpkg] and as long as your package has a name and link in the bellrepos.txt file, you can just type the name of the package for an easy installation!
--------------------------------------------------------------------------------------
Current dependencies include:
GNU awk
GNU wget
GNU coreutils
GNU tar
GNU make (for now. There are plans to have multiple compilers supported.)
Either sh/bash to be installed
A unix-like system
--------------------------------------------------------------------------------------
Commands:
installpkg (Download and install packages)
reinstallpkg (Reinstall packages saved in the cache)
cache (Allows you to clear your package cache)
removepkg (Remove packages and their residual files. Currently unfinished)
version (Shows version information)
help (Shows the "Bell Help Pane")
updatepkg (Updates sources and packages. Not implimented yet and may take a while)
--------------------------------------------------------------------------------------
Roadmap for bell-pkg:
Dependency tracking (Needed and a priority feature)
----
Proper loading indicator (Not strictly needed, but would be fun and silly)
----
Support for more compilers (I need to learn the compilers before adding them, but it is also a priority feature)
----
Native HTTP|HTTPS|FTP file retriever (Not needed whatsoever, but allows for less dependencies)
----
Pre-compiled binary packages (I would need a site to host those packages and I would need a bigger community behind bell-pkg to compile the packages and add them to said repo. If anyone wants to help, send me a message please. It would be greatly appreciated. :3 )
----
Bootstrapper/installer (Designed for any LFS users, but also because I would like to make my own distribution centered around bell-pkg)
----
Proper config file (For people to choose their autenticator such as "Sudo" or "Doas" and a few other options so anyone can customize bell-pkg to their liking :3 )
---------------------------------------------------------------------------------------
bellrepos.txt text format:
----
(pkgname) (downloadlink)
---------------------------------------------------------------------------------------
