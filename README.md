# Location Models
Example codes for facilities courses at Oklahoma State University (IEM 4203/5203). All codes are written in Python, use NetworkX for handling graphs, and solve linear and integer programs using the Gurobi optimizer.

## NetworkX Codes
1. [NetworkX_Basics](https://github.com/AustinLBuchanan/Location_Models/blob/main/NetworkX_Basics.ipynb)
   - Creates a directed graph in NetworkX, adds nodes, adds (weighted) edges.
   - Writes the graph to an external .json file and reads it back in.
2. [NetworkX_Distances](https://github.com/AustinLBuchanan/Location_Models/blob/main/NetworkX_Distances.ipynb)
   - Reads a directed graph from an external .json file.
   - Calculates edge-weighted distances.
   - Finds (single-source) shortest paths.
3. [NetworkX_Roads](https://github.com/AustinLBuchanan/Location_Models/blob/main/NetworkX_Roads.ipynb)
   - Calculates distances in a [large undirected road network from Colorado with 1 million edges](http://www.diag.uniroma1.it/challenge9/download.shtml).

## Gurobi Codes
1. [Gurobi_Shortest_Path](https://github.com/AustinLBuchanan/Location_Models/blob/main/Gurobi_Shortest_Path.ipynb)
   - Reads a directed graph from an external .json file.
   - Solves shortest path problem as an integer program, and then as a linear program.
2. [Gurobi_Transportation_Problem](https://github.com/AustinLBuchanan/Location_Models/blob/main/Gurobi_Transportation_Problem.ipynb)
   - Solves transportation problem (for drum sets) as a linear program.
3. [Gurobi_kMedian](https://github.com/AustinLBuchanan/Location_Models/blob/main/Gurobi_kMedian.ipynb)
   - Solves k-median problem as an integer program.
   - Random instance has 100 sites and 1,000 demand points in the plane.
   - Forces Gurobi to solve the LP relaxation using concurrent method.
   - Visualizes instance and solution using matplotlib.
4. [Gurobi_Uncapacitated_Facility_Location](https://github.com/AustinLBuchanan/Location_Models/blob/main/Gurobi_Uncapacitated_Facility_Location.ipynb)
   - Solves uncapacitated facility location problem as a mixed integer program.
   - Random instance has 100 sites and 1,000 demand points in the plane.
   - Forces Gurobi to solve the LP relaxation using concurrent method.
   - Visualizes instance and solution using matplotlib.
5. [Gurobi_Capacitated_Facility_Location](https://github.com/AustinLBuchanan/Location_Models/blob/main/Gurobi_Capacitated_Facility_Location.ipynb)
   - Solves capacitated facility location problem as a mixed integer program.
   - Random instance has 100 sites and 1,000 demand points in the plane.
   - Forces Gurobi to solve the LP relaxation using concurrent method.
   - Visualizes instance and solution using matplotlib.
6. [Gurobi_Set_Cover](https://github.com/AustinLBuchanan/Location_Models/blob/main/Gurobi_Set_Cover.ipynb)
   - Solves set cover problem as an integer program. 
   - Toy instance asks to locate a minimum number of ambulances to guarantee an 8-minute response time.
7. [Gurobi_kCenter](https://github.com/AustinLBuchanan/Location_Models/blob/main/Gurobi_kCenter.ipynb)
   - Solves k-center problem as a mixed integer program. 
   - Toy instance asks to locate 3 ambulances to minimize the worst-case response time.
8. [Gurobi_Max_kCover](https://github.com/AustinLBuchanan/Location_Models/blob/main/Gurobi_Max_kCover.ipynb)
   - Solves max k-cover problem as an integer program.
   - Toy instance asks to locate 3 ambulances to maximize coverage within a 3-minute response time.

