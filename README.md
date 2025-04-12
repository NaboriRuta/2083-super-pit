# 2083-super-pit
#### Design by Shelton Adams
#### To download these files, download git and run this command in your computer's terminal:
```
git clone https://github.com/NaboriRuta/2083-super-pit/
```


## Some important things to note:
- Parts modeled can all be found at [The DIY Road Cases Store](https://diyroadcasesstore.com)
  - Some dimensions weren't included, but everything is as accurate as possible
  - I'd suggest looking at [Penn-Elcom](https://penn-elcom.com) for more parts because they have more parts and the DIY Road Cases Store gets basically everything from them
- The plywood our team used is 15/32" thick
- Dimensions are rounded down to the nearest 1/16"
- When it comes to placements of tongue and groove extrusions: All tongue extrusions are on the main bottom compartment and groove extrusions are everywhere else

## Quick File Description
- plywood-cut-lists contains a cut list of how the pieces are cut out initially as well as what the finished pieces will end up looking like
- swx-files contains all of the SOLIDWORKS CAD files used
- step-files contains the main sections of the SOLIDWORKS files, just in .STEP format so it's compatible with all CAD software
- model-pics contains pictures of the Super Pit for people who don't have SOLIDWORKS or any form of CAD on their computer

## For CAD People
- You will notice parts like "Tongue Extrusion Alt 1"
  - These are so the assemblies don't make a bunch of errors when rebuilding
- Some designs were too detail-intensive to do from scratch, so you'll see lots of boxes with the same overall dimensions and the name carved out
- Due to all dimensions being rounded down to the nearest 1/16", there are gaps between:
  - Edges where aluminum extrusions meet
  - the pit pieces themselves when the full assembly is in its closed state
- Each piece does need to be changed individually. Adding global variables to dimensions unfortunately breaks everything
- If you're changing the design to be less than 4' tall/wide, the back wall of the front half no longer needs to be two separate pieces
- Cut Lists can be changed to fit pieces differently, if you're changing the CAD at all
- step-files doesn't contain all of the files used due to the nature of how step files work
  - Separate documents can be made for the individual parts outside of the assembly

#### If you have any questions, feel free to respond to the Delphi Post (Not Out Yet) or message me via Discord (@naboriruta)
