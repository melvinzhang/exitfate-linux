## Exit Fate Linux port fixes

Exit Fate was created by SCF using RPG Maker XP. The Windows version can be found at http://site.scfworks.com/?page_id=10

RadialApps ported the Windows version to Linux and Mac. They can be found at https://radialapps.com/linux/exitfate.html and https://radialapps.com/mac/exitfate.html respectively.

The Linux version contains a number of new bugs introduced by the porting process. This repo fixes some of these bugs.

### Bug: Crash when opening units stats page

One of the screens in the game shows the stats of each unit you have recruited.

Opening this screen in the Linux version crashes the application. This has been fixed.

### Bug: Party formation is reset when changing party members

Any change in party members causes the party formation to be reset. This requires the player to reposition every member and quickly becomes tedious.

In the Windows version, only the position of the new party members have to be set, the existing members stay in the current position.

The behavior of the Linux port now follows the Windows version.

## Updating the Linux port

To incorporate the fixes into the Linux port, download (Game103.zip)[https://github.com/melvinzhang/exitfate-linux/releases/download/1.03/Game103.zip] and unzip the contents into your exitfate directory.

This creates two new directories, Data and Graphics. Then rename Game.rgssad to Game.rgssad.bak so that the engine will use the files from Data and Graphics directories.

## Remaining bugs present in all versions

See http://exitfate.webs.com/guides/errors.htm
