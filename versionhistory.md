---
layout: page
title: "Version History"
permalink: /versionhistory/
---

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