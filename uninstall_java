#!/data/data/com.termux/files/usr/bin/bash

#Setup
shopt -s expand_aliases
alias ee='echo -e'

#Greetings
echo
ee "\e[93mThis script will uninstall Java from Termux."
echo

#Checking for existing Java installation
if [ ! -e $PREFIX/bin/java ]
then
	ee "\e[32mJava is not installed!"
	echo
	exit
else
	#Actual uninstallation
	ee "\e[32m[*] \e[34mUnseting %JAVA_HOME%..."
	unset JAVA_HOME=$PREFIX/share/jdk8
	echo "WARNING! THIS SCRIPT WILL UNSET THE %JAVA_HOME% ONLY TEMPORARILY! I STRONGLY RECOMEND YOU TO REMOVE \"export JAVA_HOME=$PREFIX/share/jdk8\" LINE FROM YOUR \"$HOME/.profile\" SETUP FILE, AS NOT DOING THAT WILL CAUSE PROBLEMS IN SOME APPS!"

	ee "\e[32m[*] \e[34mRemoving Java..."
	rm -drf $PREFIX/share/jdk8
	rm $PREFIX/bin/jar
	rm $PREFIX/bin/jarsigner
	rm $PREFIX/bin/java
	rm $PREFIX/bin/javac
	rm $PREFIX/bin/javadoc
	rm $PREFIX/bin/javah
	rm $PREFIX/bin/javap

	echo
	ee "\e[32mJava was successfully uninstalled!\e[39m"
	echo
fi
