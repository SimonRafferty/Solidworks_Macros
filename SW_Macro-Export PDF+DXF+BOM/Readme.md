Given an assembly of sheet metal (and other) parts, this will optionally export all the 2D Drawings as PDF's
then find all the Sheet Metal parts & export flat patterns for them.

NOTE: It does not work on (horrible!) Multi-body parts, sheet metal or otherwise.

It will also create a BoM (as a CSV File) for the sheet metal parts in a format friendly to Laser Cutting & folding shops.

The Flat Patterns are exported with a file name such as 6mm (Mild Steel) 23 Off - Widget.dxf
Based on the material and material thickness from the model.  This format is also friendly to laser cutting shops who cannot figure out how to open the BoM.  Remember to specify the material in the part, otherwise they default to 'mild steel'.

I've also included an icon in case you want to add it to a toolbar
