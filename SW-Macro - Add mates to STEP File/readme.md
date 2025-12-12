If you import a STEP file, for example a part you've downloaded, all the parts in the assembly are fixed in place & there are no mates.

This macro first of all sets all but the first part in each sub-assembly to be floating, analyses the geometry and adds a set of plausible mates.

First it adds concentric mates where the bore and OD of the two parts are within 4mm of one another
Then is adds coincident mates to parts where their bounding boxes overlap or touch one another
Lastly it adds distance mates wher the faces are parallel and between 0,02mm and 100mm apart.

It looks to see if any of the mates have over-defined the model and removes the problem ones.

I've tried this on several files (castor wheels for example) plus a medium sized assembly someone exported from Fusion.  It seems to get it more right than wrong - and where it's wrong it's easy to tidy up.
