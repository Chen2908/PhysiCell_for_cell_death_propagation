# **Cells_Verticles** : a .csv file containing the following information for each cell:
	1. Cell index, from 1 to n, where n is the total number of cells in the simulation
	2. Cell position in a 2 diamentional plane (x,y)
	3. Time of Nucleation
	4. Time of death
	
*The time of death, taken from the experiment, will be used for verification purpose only.
	
# **Cells_Edges** : a .csv file containing a match between indexes of neighbor cells.
	There is a corresponding line in the file for each edge (Ci, Cj).

	
V= { C1,...,Cn }

E= { (Ci,Cj) : i,j =1...n , i!=j }  (Celli and Cellj are neighbors)

Example graph:

![Graph](/Cells_graph4.jpg)
