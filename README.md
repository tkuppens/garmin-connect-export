garmin_sync
===========

Download your Garmin Connect gpx files and stats

Description
-----------

Pragmatic script to extact gpx files and stats from Garmin Connect. wget needs a cookie provided from a browser session. Script downloads the gpx files. If for some reason there is no gpx file associated to an activity in Garmin Connect (eg. no GPS data), the GC activity id is thrown in error and ignored. The already downloaded activity ids are listed so only new activities are being downloaded.


Use
---

garmin [cookiefile]

cookiefile: must contain the Netscape-style cookie. The name of the cookie file will also be the name of the local activity db.  

Downloaded gpx file will be named [date][activity_id][activity_type].gpx 

A csv stats list will be created named [cookiefile].csv

