# Javafox

Java is going out of style and yet is needed to manage many different lights out management systems such as HPs iLO and such.  To be able to continue manage hardware some specific combinations of browsers and java is needed.

1. Clone this repository
1. Get Firefox ESR 52 from here: https://www.mozilla.org/en-US/firefox/organizations/all/ - this version of Firefox still supports the java plugin
1. In the checked out repository unpack your java tarball so that it is unpacked in a "firefox" directory.
1. To allow Java to run the unsecurely and out-of-date signed java apps you need to make security exceptions.   Make a file called "exception.sites" in this kind of format:

```
https://192.168.254.0
https://192.168.254.1
```
