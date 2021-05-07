# Termux Java

### Information

This script will install Java in Termux.

Libraries compiled by [Hax4us](https://github.com/Hax4us "Hax4us's GitHub profile"), scripts written by [Hax4us](https://github.com/Hax4us "Hax4us's GitHub profile"), [MasterDevX](https://github.com/MasterDevX "MasterDevX's GitHub profile") and [Guzio](https://github.com/GuzioMG "Guzio's GitHub profile"), with some *very, very tiny* help from [Harshiv-Patel](https://Harshiv-Patel "he changed like... one thing").

### How to Install

To install Java, open Termux and execute the following command:

```pkg install wget && wget https://raw.githubusercontent.com/MasterDevX/java/master/installjava && bash installjava```

> If you have ```wget``` already installed, run ```wget https://raw.githubusercontent.com/MasterDevX/java/master/installjava && bash installjava``` to install Java.

> Or just ```bash installjava``` if you already have the script downloaded.

When installed, run ```java -version``` to check the version of Java, usually is ```java version "1.8.0_152"```, if it's correcty installed. If it gives you a different output, procede to the troubleshooting steps.

After checking that Java works, it means that you were able to install Java successfully!

### How to Uninstall

We provide an uninstall script. To uninstall java, run this command. 

```wget https://raw.githubusercontent.com/MasterDevX/java/master/uninstall_java && bash uninstall_java```

You may only run ```bash uninstall_java``` if it's already installed.

### Troubleshooting

(If your issue isn't here, open an issue in the GitHub Issues Tab.)

"Bad System Call"

[*From issue #39*](https://github.com/MasterDevX/Termux-Java/issues/39)

[*Thanks kcubeterm for awnsering the issue*](https://github.com/kcubeterm)

Use ```proot```. To install it, simply run ```pkg in proot```.

After that, execute the command ```termux-chroot``` with nothing after it.

You may now attempt to run the Java Command.

(MORE ISSUES ADDED SOON)
