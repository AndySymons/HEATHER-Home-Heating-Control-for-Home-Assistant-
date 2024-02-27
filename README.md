# Heating-X2-code-generator
Installation aid for the Home Assistant Blueprint **Heating X2**

Uses Microsoft Mail Merge to create YAML files for all the template sensors and helpers required for a complete home heating system using the Home Assistant Blueprint **Heating X2** for each room. Microsoft Office (WORD and EXCEL) is a prerequisite (sorry I could not find a free package to do this) 

**Version 2.1** was still compatible with Heating X2 but added new features 
- Zone control -- binary sensors and automations
- All thermostats for a room listed in room automations and dashboards 
- All thermostats for a zone listed in zone binary sensor groups
- Separate deshboard generation files for view and cards (same code, differnet indents)
- Guide to setting up a home smart heating system, in addition to updated instructions on how to use the code generator 

**Version 2.2** is still compatible with version 2.1 but adds one feature 
- Logging of the actons of the heating automations into one or more log files 
  
To get started download the ZIP file to a temporary location on a local disk drive (e.g. the downloads folder) and unzip it. Problems can occur if it is used on a drive that is synchronised to a cloud service, such as iCloud or OneDrive.

In the resulting folder there is a Guide, an EXCEL data file and a WORD mail merge file for each YAML file. 

Please see the *Guide* inside the package for tips on setting up a full home smart heating system and details of how to use the code generator. 
