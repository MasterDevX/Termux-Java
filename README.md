[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code%20(for%20some%20reason)-blue?logo=gitpod)](https://gitpod.io/#https://github.com/MasterDevX/Termux-Java)

# Termux Java

### Information

This script will install Java in Termux.

Libraries compiled by [Hax4us](https://github.com/Hax4us "Hax4us's GitHub profile"), scripts written by [Hax4us](https://github.com/Hax4us "Hax4us's GitHub profile"), [MasterDevX](https://github.com/MasterDevX "MasterDevX's GitHub profile") and [Guzio](https://github.com/GuzioMG "Guzio's GitHub profile"), with some *very, very tiny* help from [Harshiv-Patel](https://Harshiv-Patel "he changed like... one thing").

### How to use

To install Java, open Termux and execute the following command:

```pkg install wget && wget https://raw.githubusercontent.com/MasterDevX/java/master/installjava && bash installjava```

> Eventually, run ```wget https://raw.githubusercontent.com/MasterDevX/java/master/installjava && bash installjava``` to install Java if you already have ```wget``` installed.

> Or just ```bash installjava``` if you have the script already downloaded for some reason.

When installed, run ```java -version``` to check, if it's correcty installed (i.e. if it throws a command not found error, it's clearly not.)

After that you can run Java using ```java``` command.

We also provide an uninstaller, but since I'm writing this while making that script, there's no way I can attach a command here, as I need a link for that. Anyway, look for ```uninstall_java.sh``` in the repo's home.
