# bell-pkg
Bell-pkg is a shell based package management system that is designed to be simple! You can install a package by invoking [bell installpkg] and as long as your package has a name and link in the bellrepos.txt file, you can just type the name of the package for an easy installation!
--------------------------------------------------------------------------------------
Current dependencies include:
GNU awk (to read @world and bellreos.txt)
GNU wget (to download tarballs)
GNU sed (to edit @world)
GNU coreutils (needed for the program to even function)
GNU tar (needed to unpack the tarballs)
GNU make (for now. There are plans to have multiple compilers supported.)
Either sh/bash to be installed (to run the binary, duh)
A unix-like system (who would use ts on winblows anyway?)
--------------------------------------------------------------------------------------
Commands:
installpkg (Download and install packages)
reinstallpkg (Reinstall packages saved in the cache)
cache (Allows you to clear your package cache)
removepkg (Remove packages and their residual files)
version (Shows version information)
help (Shows the "Bell Help Pane")
updatepkg (Updates sources and packages. Not implimented yet and may take a while)
bootstrap (Installs the bell-pkg binary as "bell" in /usr/bin/ and creates not only the /etc/bellpkg directory, but also the @world and bellrepos.txt files)
--------------------------------------------------------------------------------------
Roadmap for bell-pkg:
Dependency tracking (Needed and a priority feature)
Support for more compilers (I need to learn the compilers before adding them, but it is also a priority feature)
Pre-compiled binary packages (I would need a site to host those packages and I would need a bigger community behind bell-pkg to compile the packages and add them to said repo. If anyone wants to help, send me a message please. It would be greatly appreciated. :3 )
---------------------------------------------------------------------------------------
bellrepos.txt text format:
(pkgname) (downloadlink)
---------------------------------------------------------------------------------------
