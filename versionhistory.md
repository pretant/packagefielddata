---
layout: page
title: "Version History"
permalink: /versionhistory/
---

***Version 2.2.0:*** (6/3/2024)
  - Updated Field Upload links.
  - Moved Flight Date entry field to second row, next to Team Number field.
  - Added step numbers in front of each button and entry label so users know the order in which to click or fill them out

***Version 2.2.0:*** (6/3/2024)
  - Updated master structure list.
  - Updated Team Number format.
  - Now generates a text file that lists all the structure IDs that are in the directory.
  - Now creates a copy of all EZ Poles and place them in a new folder "EZPolesForTrans".

***Version 2.1.12:*** (6/3/2024)
  - Updated master structure list.

***Version 2.1.11:*** (5/8/2024)
  - Bug fix regarding OH- prefixes.

***Version 2.1.10:*** (5/7/2024)
  - Updated structure master list.
  - Minor bug fixes and improvements.

***Version 2.1.9:*** (4/11/2024)
  - Updated structure master list.
  - Minor bug fixes and improvements.

***Version 2.1.8:*** (3/13/2024)
  - Fixed a bug causing completed zip files to be erroneously canceled and deleted.
  - Minor bug fixes and improvements.

***Version 2.1.7:*** (3/12/2024)
  - Added new GIS structures to the list
  - Minor bug fixes and improvements.

***Version 2.1.6:***
  - Added a "Cancel Zipping" button that stops the zipping process and deletes the partially zipped folder.
  - Script can now be used offline.
  - Minor bug fixes and GUI improvements.

***Version 2.1.5:***
  - Added a "Copy" function when user right-clicks on the textbox area.
  - Removed RTV functionality.
  - Minor bug fixes and GUI improvements.

***Version 2.1.4:***
  - Team Number field is now limited to 101 to 199 or 501 to 599.
  - Added printed information for each folder.
  - Fixed a bug where structure ID's with no 'E' suffix (transmission towers) are not found in GIS
  - Minor bug fixes and GUI improvements.

***Version 2.1.3:***
  - For multiple structures issues, the farthest distance number and the farthest image name are now added to the printed text
  - Script now only renames the folder after all issues are fixed (right before zipping).
  - Fixed a bug where script is not able to compare image dates and flight date 
  - Minor bug fixes and GUI improvements.

***Version 2.1.2:***
  - Fixed a bug where script is not recognizing multiple structures in a folder properly
  - Minor bug fixes and GUI improvements.

***Version 2.1.1:***
  - Minor bug fixes and improvements.

***Version 2.1.0:*** (What the script does:)
  - Name and zip data folder properly (regular vs RTVs)
  - Summary of issues is listed and in red fonts
  - Copy structure IDs to paste in Upload Check
  - Delete hidden Mac files
  - Check for missing N on nadir
  - Check for potential misnamed folders
  - Check for incorrect image dates
  - Calculate distance of nadir coordinates from GIS stucture coordinates and flags user if distance is greater than 500 ft.
  - Separate EZ poles from regular structures (Distro only EZ Poles, Trans only EZ Poles, and EZ Poles in both)
  - Provide links to Upload Check page, Field Uploads page, and EOD form page for distro and trans

***Version 2.0.0:***
  - New and improved UI.
  - Removed "Copy" button.
  - Added "Copy Structure IDs" button that copies the folder names (structure IDs) of the folders in the directory.
  - The text box now shows the list of structure IDs in the directory once the directory is chosen.
  - Minor bug fixes and improvements.

***Version 1.2.2:***
  - Added buttons that will direct users to EOD and Weekend Travel Home Forms.

***Version 1.2.1:***
  - Zipping now includes the main folder in the zipped file (i.e., when you open the zipped file, you'll see one folder that contains the structure folder. Before, you'll see the structure folders right away).

***Version 1.2.0:***
  - Added functionality to check if all asset folders have N's in them.
  - Added functionality to check if asset folder names are in accordance with GIS structure IDs.

***Version 1.1.0:***
  - App now updates online

***Version 1.0.0:***
  - The app is inteded to name the zipped folder properly
  - The app deletes hidden Mac files and zips the folder