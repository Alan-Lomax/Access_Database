# Access Database
## Content Management For Trains

This database implements an asset management system for model trains.
The main concept is that there 'entitites' which can be either locos or rolling stock.
There are lots of data fields for capturing relevant information. 
A tabbed form is used to divide the collected information into related sections.
The majority of this is optional.

## Technical
The Access database needs the Access runtime to operate.
You need to own Access (part of Microsoft Office) if you want to modify the database.
There are two files that operate together (both are actualy Acces databases).
The front end (FE) only has forms reports and queries ... but not the main data tables.
The back end (BE) only has the main data tables.
This structure allows improvements to the front end while preserving your data in the back end.

## Trains
You can combine entities into trains (typically one loco and one or more items of rolng stock. (again totally optional)
 
## Maintenance
For each entity you can track maintenance records to capture a history for each entitiy (again totally optional)

## SNAG
During an operating session you may have snag occur (a snag is anything that needs follow up).
You can use the database to track snags until they are closed. (again totally optional)

## RFID
You can define locations around your layout and assign them each an RFID reader
You can define RFID tags (manually) or easily by simply attaching it to an entity and scanniong it in.
In the latter case the scan will create an RFID tag object, but it will be assigned to the 'undefined' entity at first.
Then you can reassigne the tag to the correct entity and futre scans will be reported correctly.

