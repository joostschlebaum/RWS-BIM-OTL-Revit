# RWS-BIM-OTL-Revit
Rijkswaterstaat BIM OTL implementation for Autodesk Revit

⚠️ **IMPORTANT** ⚠️
This database is in development. Features might be missing.


## Overview
The Dutch highways agency Rijkswaterstaat is working on standardizing BIM deliveries in such a way that it is usable from design all the way to asset management.
One of the key elements for this implementation is the Object Type Library (OTL).
- https://otl.rws.nl/publicatieomgeving/#/

This database makes use of the Revit Classification Manager:
- https://www.biminteroperabilitytools.com/classificationmanager.php


## Installation
- Install the Revit Classification Manager https://www.biminteroperabilitytools.com/classificationmanager.php#download
- Download the Excel file of the database and place it in a convenient location


## Project initialization
- Open the Revit Classification Manager Setup menu inside of your Revit project
- Browse to the Excel file and select it 
- Click finish. This will now automatically add the required shared parameters to the Revit project


## Example usage
- Open the Revit Classification Manager Assign menu inside of your Revit project
  (You can leave this window open for as long as you like and even move it to a second screen)
- Select the Revit element(s) you want to assign an object type definition to
- In the classification manager, in the left menu select Element
- Depending on which parameter you want to set and depending on the hierarchy, select either the Systeemdelen (lvl 4), Bouwdelen (lvl 5) or Constructiedelen (lvl 6) tab.
  (Some parameters can only be mapped to a specific Revit type. Those types will automatically be filtered on their respecitive tab)
- Select the object information in the list that you want to assign to the selected Revit element and click Assign


## Notes
- You can assign all 3 levels separately
