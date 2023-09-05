# TSPDL
New instances used by M. A. Boschetti and S. Novellani in the work: _Last-mile delivery with drone and lockers_ (2023).

1) Branch MC10_2 contains the instances with nine customers and up to two lockers.
They are divided into three network types: 37, 40, and 43, as per the paper where they originated (Murray and Chu 2015 https://doi.org/10.1016/j.trc.2015.03.005). In such a paper, their original version was used to solve the _flying sidekick traveling salesman problem (FSTSP)_.
Each folder contains three files:
  a) tau.csv and tauprime.csv: those are the distance matrixes of the truck and the drone, respectively.  
  b) nodes.csv, where each row represents a node: 0 is the depot, nodes from 1 to 9 are the customers, and 10 and 11 are the lockers (note that if only one locker is used, then 11 is ignored). For each row, the first value is the node_id, the second and third are the x and y coordinates, and the last value for the customer nodes is 0 if dronable and 1 otherwise.

2) Branch MC20 contains instances with 19 customers and up to 3 lockers.
They are instances that originated from the paper by Murray and Chu (2015) (https://doi.org/10.1016/j.trc.2015.03.005) used for testing the _parallel drone scheduling TSP (PDSTSP)_.
Each folder contains three files:
  a) tau.csv and tauprime.csv: those are the distance matrixes of the truck and the drone, respectively.  
  b) nodes.csv, where each row represents a node: 0 is the depot; nodes from 1 to 19 are the customers; 20, 21, and 21 are the lockers (note that if only one locker is used, then 21 and 22 are ignored, while if only two lockers are used, then only 22 is ignored). For each row, the first value is the node_id, the second and third are the x and y coordinates, and the last value for the customer nodes is 0 if dronable and 1 otherwise.

All other needed data are described in our paper.
