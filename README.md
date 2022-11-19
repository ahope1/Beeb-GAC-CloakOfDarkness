# Cloak Of Darkness in GAC for the BBC Micro 
[**Cloak Of Darkness**](https://mipmip.org/IFrescue/rf/) is the de-facto standard demo of a text adventure game or work of interactive fiction (IF). Cloak Of Darkness is implemented here in [Graphic Adventure Creator](https://en.wikipedia.org/wiki/Graphic_Adventure_Creator) ([GAC](https://stardot.org.uk/forums/viewtopic.php?p=181239#p181239)) for the 8-bit BBC Micro computer. 

[**>>> Play the game online <<<**](http://bbcmicro.co.uk//jsbeeb/play.php?autoboot&disc=https://raw.githubusercontent.com/ahope1/Beeb-GAC-CloakOfDarkness/main/CloakOfDarknessGAC.ssd)

[General instructions](https://stardot.org.uk/forums/viewtopic.php?p=181239#p181239) for using the BBC Micro version of GAC are available. GAC was originally developed by [Sean Ellis](https://www.skeptic.org.uk/2020/11/sean-ellis-1966-2020/) (1966-2020). RIP. 

Cloak Of Darkness was originally designed and implemented (in other IF systems) by [Roger Firth](https://www.ifwiki.org/Roger_Firth).


## The files

***CloakOfDarknessGAC.ssd*** is a bootable disc-image file (in Acorn DFS format) that can be used with a real BBC Micro computer or with a BBC Micro emulator such as [BeebEm](http://www.mkw.me.uk/beebem/) or [JSBeeb](https://bbc.godbolt.org). If you boot the disc-image (**EXEC O.!BOOT*) and run the GAC adventure editor, you'll be able to load, view and edit the file CLOAK, which contains all the data for the game (except the number of the Starting Room, which is 4).

[**>>> Run the editor <<<**](http://bbcmicro.co.uk//jsbeeb/play.php?embedBasic=*EXEC%20O.!BOOT%0A&disc=https://raw.githubusercontent.com/ahope1/Beeb-GAC-CloakOfDarkness/main/CloakOfDarknessGAC.ssd)

***printout.txt*** is a file containing the implementation details of the game (as contained in the aforementioned file CLOAK), exported via the Print menu in the BBC Micro version of GAC, and edited slightly. 
