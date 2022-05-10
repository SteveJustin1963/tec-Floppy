# tec-Floppy
### project
Allow the tec1 using MINT and/or ASM code to access and use an old 5.1/4 inch floppy drive or a 3 1/2 inch FDD, the old fashoned way, with an IO circuit. Then read and write to the disk.

"The most common capacity of the 5¼-inch format in DOS-based PCs was 360 KB...In 1984, IBM introduced ...1.2 MB 5¼-inch", right where the Tec-1 was born, so thats period correct.... "...the 720 KB double density 3½-inch microfloppy... 1986 and 1.44 MB high-density ... in 1987." so lets use that for the Tec-1.
I like the RC2014 floppy controller so will adapt this.

### Hardware
Use https://www.smbaker.com/z80-retrocomputing-part-14-rc2014-floppy-controller-boards to make our project. "The reduced complexity of the WD37C65 circuit is evident from the lower chip count. It’s not earth shattering, but any simplification is a benefit. In addition, having the DOR register built into the chip seems to make the programming easier."

![](https://github.com/SteveJustin1963/tec-Floppy/blob/main/docs/New%20folder/rc2014-floppy-wd-sch.png)

### Software
model code after "floppy driver from RomWBW" (https://github.com/wwarthen/RomWBW) and or the "Grant Searle CP/M monitor, BIOS and tools...has closer compatibility to RC2014". 





## Ref
- https://en.wikipedia.org/wiki/Floppy_disk
