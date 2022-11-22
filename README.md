# ClusteringVelibStations
The velib system is a sharing system of electric bikes distributed across Paris. A velib station has multiple electric bikes that a registered user to the Velib service, can locate on the application and use them. When a user is done with their bike, they can drop it at any velib station to load them.

In this project, we analyze the loading profiles of the vélib stations to catch some insights on its overall use and build a client segmentation.

The result of this study could serve in adjusting the installation of future stations and finding new appropriate products & services by user profile. 

The project is written in R and Markdown


## Dataset
The given dataset named *velib* is made up of 4 useful sections:
*1) data:* Loading profiles of the bike stations over one week. The values are normalized between 0 and 1 and collected every hour during the period from Sunday 1st Sept. to Sunday 7th Sept., 2014.
*2) Position:* Longitude and Latitude of each velib station  
*3) Date:* Date of recording
*4) Names:* Name of the velib stations


## Approach
Firstly, we will do any pretreatment and descriptive analysis. It will also take into account any useful data and feature extractions.  Particularly, the Principal Component Analysis is chosen for this last task.
Secondly, we will apply a set of clustering algorithms to find meaningful clusters and compare among the algorithms thanks to their respective results. The various clusters will be represented on a map to gain additional understating of the segmentation given by the clustering algorithms.


## Models
The goal is to get the most interesting clustering by navigating through models such as :   
- Hierarchical clustering
- K-Means


## To run the project
* Run the file *velib_stations_clustering.Rmd*   


## Closing
Feel free to comment and add any constructive critics that could help me better my solution :)    



