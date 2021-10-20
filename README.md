# PCB-Board-Outlines
PCB Board Outlines in DXF format for import into E-CAD software

I haven't updated this archive in a very long time, a number of other things got in the way and it just hasn't been on my mind. That said, as of 2021, I'm working hard on a bunch of new products and projects, so I was going through my archives, and figured I'd update this a bit.

Notes:

* Most of what I design is intended for imperial measurement, that said, I did my best to pick dimensions that were at, or close to a metric equivalent, such that using a smaller-sized screw would allow any particular board design to work with both.

* All of the sub-2" (50.8mm) boards are intended to use #2-56 screws with a .096" (~2.2mm) clearance hole size. #2 standoffs have kinda become my internal standard for a lot of the projects I build and work on, and using the smaller sized screw allows me to save weight, which is of critical concern when building aerospace components. also, that means less space required for screws, and more room for parts. This is important if you're using OSHPark or another vendor which charges you by the square inch. Personally, I highly highly recommend going with OSHPark for all your board fab needs. (if you're in the US) They have been a critical partner for me.

* I have opted to publish both the dxf files, as well as the solidworks part files, in the future I may also make these available as STL's however, it's probably easier to use KICAD's PCB2STL function. If you are using Solidworks circuits or another product, this should make integration fairly easy without having to contend with SW's kludgy importation system. Also it should be fairly straight-forward if using Fusion360, etc.

* This archive is targeted mostly towards my work with both KICAD and Solidworks in machine and aerospace design. There is the beginnings of a Solidworks 1U cubesat in the Solidworks folder, this conforms to Revision 12 (and probably others) of the Cubesat CDS: https://srl.utu.fi/AuxDOC/tke/radmon/cubesat_standard.pdf

* The "Reference Sheets" folder contains datasheets for the 16x02 and 20x04 displays that are commonly used with Arduino and the like. The "Motherboard..." file is intended to attach to either of those displays with standoffs making a sort of back-pack. I normally connect the display via I2C, so I didn't include a means of aligning the pins from the display. I might add that later... 

Anyways, use away, have fun, don't get in trouble, tip your waitresses, and support your local animal shelters. I am reachable at drew@ammomfg.com
