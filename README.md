# DownloadPortalFeatureService
Downloads a feature service (As file geodatabase, Shapefile or CSV) from a portal site and optionally updates an existing dataset. Two update options:
        
* Existing Mode - Will delete and append records, so field names need to be the same.
             
* New Mode - Copies data over. Requires no locks on geodatabase datasets being overwritten.  