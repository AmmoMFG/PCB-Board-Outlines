INTRODUCTION
------------

This is a series of board outlines in standard DXF format, it is provided for
as a bridge between the mechanical CAD world and the electrical CAD world.

Included are a series of outlines suitable for import into KICAD, Eagle, or
any other electrical CAD system capable of understanding and working with DXF
files.

All files use a metric format internally, but all outlines are done in inches.
Each board contains mounting holes of .140" (suitable for common stand-offs)
that are 1/8" (.125") from the corners, and each corner has a 1/8" radius.

REQUIREMENTS
------------

Some kind of E-CAD system capable of understanding DXF files

INSTALLATION
------------

Put files in a directory where you can import them into your project. 
$HOME/PCB/Board_Outlines has worked well in the author's use.

TROUBLESHOOTING
---------------

The DXF format as exported by certain mechanical CAD programs does not preserve
the unit measurement. KICAD defaults to millimeters, thus all of these files 
have been created assuming a MM is the unit they will be imported as. If
given the option to import with a defined unit, select MM.

REQUESTS
--------

If you would like a board with a specific geometry, feel free to e-mail or put
in a feature request.


MAINTAINERS
-----------

* Andrew Van Lahr (Drew) - drew@ammomfg.com 

This project is sponsored by Ammunition Manufacturing Products as a means
to give back to the Open-Source community who have done so much to make small
manufacturing possible. 