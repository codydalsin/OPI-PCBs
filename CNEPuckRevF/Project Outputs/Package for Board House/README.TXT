Notes:
======

1)	Internal Plane Layers are negatives.

2)	Vias on this PCB are tented.

3)	*** IMPORTANT *** This PCB fits into a plastic enclosure with tight tolerances.  Any breakaway tab edges that protude
	from the OUTSIDE edge of the PCB have to be manually removed by OPI so that the outer edge is smooth
	before the unit	is installed in the pastic enclosure.

	This PCB has four (4) copper and internal plane relief areas that mouse bytes can be installed.  The
	intent here is that the shard breakaway section can be INTERNAL to the edge of the PCB and not have
	to be manually filed or otherwise removed by production personel.

	Suggested drill size for the mouse bytes is 0.024".

4)	All holes are specified FHS.

5)	Layer Stackup of this PCB is as follows:

	Component Side Copper
	Internal Layer 1
	Internal Layer 2
	Solder Side Copper

Customer name:	OPI Systems
Contact:	John Bobbett
Address:	1216 - 36 Avenue N.E.
		Calgary, Alberta
		Canada T2E 6M8
Email:		johnb@opisystems.com

PCB Number	CNEPuckRevF

# of Files:	32 with README (excluding ODB files)

Data Format of the Gerber and NC Drill Files is as follows

	Data Code:		ASCII
	Data Format:		2.3
	Mode:			ABSOLUTE
	Units:			INCHES
	Zero Suppression:	LEADING

Description of Files and Directories in ZIP File
================================================

***
*** Please Note that some files (such as status files generated by the Altium CADD Package)
*** are NOT required for the PCB manufacturing process.
***

	DRC
	===
		CNEPuckRevF.html					-->	Altium Design Rule Check Output File

	Gerber
	======
		CNEPuckRevF.APR						-->	Aperture List
		CNEPuckRevF.APR_LIB					-->	Aperture Library List

		CNEPuckRevF.GBL						-->	Gerber Bottom Layer Routing
		CNEPuckRevF.GBO						-->	Gerber Bottom Layer Overlay
		CNEPuckRevF.GPB						-->	Gerber Bottom Layer Pad Master
		CNEPuckRevF.GBP						-->	Gerber Bottom Layer Paste Mask
		CNEPuckRevF.GBS						-->	Gerber Bottom Layer Solder Mask

		CNEPuckRevF.GD1						-->	Gerber Drill Drawing
		CNEPuckRevF.GG1						-->	Gerber Hole Placement - Drill Guide

		CNEPuckRevF.GP1						-->	Gerber Internal Plane 1 Layer
		CNEPuckRevF.GP2						-->	Gerber Internal Plane 2 Layer

		CNEPuckRevF.GKO						-->	Gerber Keepout Layer
		CNEPuckRevF.GM1						-->	Gerber Mechanical 1 Layer - PCB Outline
		CNEPuckRevF.GM2						-->	Gerber Mechanical 2 Layer
		CNEPuckRevF.GM4						-->	Gerber Mechanical 4 Layer
		CNEPuckRevF.GM11						-->	Gerber Mechanical 11 Layer

		CNEPuckRevF.GTL						-->	Gerber Top Layer Routing
		CNEPuckRevF.GTO						-->	Gerber Top Layer Overlay
		CNEPuckRevF.GPT						-->	Gerber Top Layer Pad Master
		CNEPuckRevF.GTP						-->	Gerber Top Layer Paste Mask
		CNEPuckRevF.GTS						-->	Gerber Top Layer Solder Mask

		CNEPuckRevF.EXTREP					-->	Gerber File Extension Description
		CNEPuckRevF.REP						-->	Gerber D-Code List

		CNEPuckRevF.RUL						-->	Altium PCB Rules Output File

	NC Drill
	========
		CNEPuckRevF-RoundHoles.TXT				-->	NC Round Hole Drill File
		CNEPuckRevF.DRR						-->	Drill Report File
		CNEPuckRevF.LDP						-->	Altium Layer Pair Output File

	ODB
	===
		Altium Generated ODB file package			-->	Altium generated ODB file package

	Status Report							-->	Altium Output Status Report
	README.TXT							-->	This File

*** PLEASE NOTE THAT SOME FILES (*.GM2, *.GPB, etc.) may not be required to produce this PCB.

Please send me an email if you have any other questions or concerns.

Thank you.

L.J. -- 05/28/14






						

 