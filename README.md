# Autodesk Master Uninstaller

**For use on Mac OS machines**
If you want to uninstall **ALL** Autodesk software from your Mac OS device you must manually delete the folders yourself. Autodesk does **NOT** have an uninstaller utility for Mac OS like they offer for Windows computers.

The full uninstall instructions can be found on [Autodesk's website](https://knowledge.autodesk.com/support/maya/troubleshooting/caas/sfdcarticles/sfdcarticles/Clean-uninstall-of-Autodesk-software-on-Mac-OS-X.html).
This script simply executes the instructions with administrator privelages easily, and verbose. 

### The commands are as follows:

1. Delete /Applications/Autodesk/ folder 
```bash
$ sudo rm -rfv /Applications/Autodesk/
```
2. Delete /Library/Preferences/FLEXnet Publisher/ folder 
```bash
$ sudo rm -rfv /Library/Preferences/FLEXnet Publisher/
```
3. Delete /Library/Application Support/Autodesk/ folder 
```bash
$ sudo rm -rfv /Library/Application Support/Autodesl/
```
4. In /Library/Preferences/ folder delete all files that start with com.autodesk, com.Autodesk, com.Alias, com.alias 
```bash
$ sudo rm -rfv /Library/Preferences/com.autodesk.*
$ sudo rm -rfv /Library/Preferences/com.Autodesk.*
$ sudo rm -rfv /Library/Preferences/com.Alias.*
$ sudo rm -rfv /Library/Preferences/com.alias.*
```
5. In /private/var/db/receipts/ folder delete all files that start with com.autodesk, com.Autodesk, com.Alias, com.alias 
```bash
$ sudo rm -rfv /private/var/db/receipts/com.autodesk.*
$ sudo rm -rfv /private/var/db/receipts/com.Autodesk.*
$ sudo rm -rfv /private/var/db/receipts/com.Alias.*
$ sudo rm -rfv /private/var/db/receipts/com.alias.*
```
6. Delete ~/Library/Application\ Support/Autodesk/  folder
```bash
$ sudo rm -rfv ~/Library/Application\ Support/Autodesk/
```

### Conclusion

Congratulations! You now no longer have anything Autodesk installed on your Mac OS device!

