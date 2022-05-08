# BeData
The files in this repository include information about the data sets described in "Robust Alternative Fuel Refueling Station Location Problem with Routing under Decision-Dependent Flow Uncertainty" by Özlem Mahmutoğulları and Hande Yaman. The data sets are generated based on the road network and population of Belgium. The locations of Belgian municipalities and the distances between municipalities were obtained from Google Maps (2021), while the populations of municipalities were obtained from the Belgian statistical office (STATBEL) (2020). 


The municipalities are regarded as the nodes of networks. Highway roads are considered as the edges of networks. The node weights are assigned based on the populations of municipalities.


The rows of "belgian_municipalities" file present information (i, name, lat, long, pop) where

          i: node number of municipality,          
          name: name of municipality,          
          lat: latitude of municipality,          
          long: longitude of municipality,          
          pop: population of municipality.


The files in the BE1, BE2, and BE3 folders contain information about the BE1, BE2, and BE3 data sets described in the aforementioned paper.  The data sets differ in nodes, edges, node weights and thus vehicle flow volumes.  
There are "nodes", "edges" and "flows" files in each folder.

The rows of "nodes" files present information (i, w) where

          i: node number,
          w: weight of node i.
          
The rows of "edges" files present information (i, j, l) where

          i, j: node numbers,
          l: length of edge between nodes i and j.
          
The rows of "flows" files present information (o, d, f) where

          o: origin of flow,
          d: destination of flow,
          f: nominal flow volume of o-d pair.
