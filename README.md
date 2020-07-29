garmin_sync
===========

Extract your Garmin Connect gpx files

Description
-----------

Quick and dirty script to extact gpx files from Garmin Connect. Cookie needs to be provided (wget) from a browser session. Script downloads the gpx files. If for some reason there is no gpx file associated to an activity in Garmin Connect (no GPS data), the activity id is thrown in error. The already downloaded activity ids are kept locally so only new activities are being downloaded.

Downloaded gpx file will be named [date][activity_id][activity_type].gpx 

Use
---

garmin [cookiefile]

cookiefile: must contain the Netscape-style cookie. The name of the cookie file will also be the name of the local activity db.  

