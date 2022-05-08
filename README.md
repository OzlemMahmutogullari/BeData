# BeData
The files in this repository include information about the data sets described in "Robust Alternative Fuel Refueling Station Location Problem with Routing under Decision-Dependent Flow Uncertainty" by Özlem Mahmutoğulları and Hande Yaman. The data sets are generated based on the road network and population of Belgium. The locations of Belgian municipalities and the distances between these municipalities were obtained from Google Maps (2021), while the populations of municipalities were obtained from the Belgian statistical office (STATBEL) (2020). 


The municipalities are regarded as the nodes of networks. Highway roads are considered for the edges of networks. The node weights are assigned based on the populations of municipalities.


Each row in "belgian_municipalities" file presents information (i, name, lat, long, pop) where

          i: node number of the municipality,          
          name: name of the municipality,          
          lat: latitude of the municipality,          
          long: longitude of the municipality,          
          pop: population of the municipality.


The files in the BE1, BE2, and BE3 folders contain information about the BE1, BE2 and BE3 data sets described in the aforementioned paper. The data sets differ in nodes, edges, node weights, and thus vehicle flow volumes.  
There are "nodes", "edges" and "flows" files in each folder.

Each row in "nodes" files presents information (i, w) where

          i: node number,
          w: weight of node i.
          
Each row in "edges" files presents information (i, j, l) where

          i, j: node numbers,
          l: length of edge between nodes i and j.
          
Each row in "flows" files presents information (o, d, f) where

          o: origin of flow,
          d: destination of flow,
          f: nominal flow volume of o-d pair.
