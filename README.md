# geo-zone-check-germany
QGIS Plugin that checks areas for UAS flight restrictions in germany
Checks a given vector layer with planned flight paths/flight areas for conflicts with nearby geographical zones in Germany and returns 2 vector layers, one with intersecting zones and one with closeby zones. Distances and links to more information about the restrictions for each zone can be found in the attribute tables. 

Known issues: Running this plugin can take 1-2 minutes, getting no response during this time isn't unusual. 

Source for geodata: DFS, BKG [2022] via www.dipul.de and their WMS service.
