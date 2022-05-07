# BeData
The files in this repository include the information of data sets described in "Robust Alternative Fuel Refueling Station Location Problem with Routing under Decision-Dependent Flow Uncertainty" by Özlem Mahmutoğulları and Hande Yaman. The data sets are generated based on the Belgian road network and population. The information regarding the locations of Belgian municipalities and the distances between municipalities was obtained from Google Maps (2021), and the information regarding the populations of Belgian municipalities was obtained from the Belgian statistical office STATBEL (2020). 


The municipalities are regarded as the nodes of networks. The highway roads are considered for the edges of networks. The node weights are calculated based on the populations of municipalities.


The columns of "belgian_municipalities" file contains information (i, name, lat, long, pop) where

          i: node number,          
          name: name of municipality,          
          lat: latitude of municipality,          
          long: longitude of municipality,          
          pop: population of municipality.


Folders BE1, BE2 and BE3 includes the files that contain the information regarding BE1, BE2 and BE3 data sets described in the aforementioned paper. The data sets differ in nodes, edges, node weights and thus vehicle flow volumes.  

Each folder has 
