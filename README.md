# Download Portal Feature Service

Downloads a feature service (As file geodatabase, shapefile or CSV) from a portal site and optionally updates an existing dataset. Two update options:
        
* Existing Mode - Will delete and append records, so field names need to be the same.
             
* New Mode - Copies data over. Requires no locks on geodatabase datasets being overwritten. 


## Features

* Download data as file geodatabase, shapefile or CSV.
* Run with or without ArcGIS Desktop installation.
* Overwrite or update existing dataset.
* Run as automated task and log start/end times.


## Requirements

* Internet access
* [Python 3.4](https://www.python.org/downloads/release/python-340/)
* ArcGIS Online/Portal named user
* Access to ArcGIS Online/Portal hosted feature service


## Installations Instructions

* Install [Python 3.4](https://www.python.org/downloads/release/python-340/) on machine.
* Fork/clone the repository or download the .zip file.
* Create a batch file based off the examples provided [here](/Examples).
* Set the parameters in the batch file:
	* 1st line - Location of python installation and location of "DownloadFeatureLayer.py" python file.
	* 1st parameter - ArcGIS/Portal site URL.
	* 2nd parameter - ArcGIS/Portal named user.
	* 3rd parameter - ArcGIS/Portal named user password.
	* 4th parameter - ArcGIS/Portal hosted feature service ID.
	* 5th parameter - Location of where to export data to.
	* 6th parameter - Data format to download - file geodatabase, shapefile or CSV.
	* 7th parameter - New or existing mode.
* Run the batch file.


## Resources

* [GitHub](https://github.com/eaglegis)
* [Twitter](https://twitter.com/eaglegis)
* [Python for ArcGIS](http://resources.arcgis.com/en/communities/python)


## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.


## Contributing

Anyone and everyone is welcome to contribute. 


## Licensing
Copyright 2016 - Eagle Technology

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.