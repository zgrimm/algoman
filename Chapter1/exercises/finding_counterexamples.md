## 1-1: 
### Show that a + b can be less than min(a, b) 

let\
	![formula](http://latex.codecogs.com/gif.latex?%24%24%5Cdisplaystyle%5C%20a%20%3D%20-1%2C%20b%20%3D%20-1%24%24 "$$\\displaystyle\\ a = -1, b = -1$$")\
Then\
	![formula](http://latex.codecogs.com/gif.latex?%24%24%5Cdisplaystyle%5C%20a%20%2B%20b%20%3D%20-2%24%24 "$$\\displaystyle\\ a + b = -2$$"), 
	![formula](http://latex.codecogs.com/gif.latex?%24%24%5Cdisplaystyle%5Cmin%28a%2Cb%29%20%3D%20-1%24%24%20 "$$\\displaystyle\\min(a,b) = -1$$ ")\
so\
	![formula](http://latex.codecogs.com/gif.latex?%24%24%5Cdisplaystyle%5C%20%5Cexists%20a%2C%20b%20%5Cin%20Z%20%3A%20a%2Bb%20%3C%20min%28a%2Cb%29%24%24 "$$\\displaystyle\\ \\exists  a, b \\in Z : a+b < min(a,b)$$")



## 1-2: 
### Show that a × b can be less than min(a, b)** 

	let a = -1, b = 5. Then a*b = -5, min(a,b) = -1 so there exist a & b such that a*b < min(a,b)



## 1-3: 
### Design/draw a road network with two points a and b such that the fastest route between a and b is not the shortest route
		
		A_________B
	    |		  |
	    C_________|

## 1-4:
### Design/draw a road network with two points a and b such that the shortest route between a and b is not the route with the fewest turns.

		A_____________________C
	  __|                     |
	 |_     _B________________|
	 	|__|

*????: What exactly is meant by route between a and b? Must all nodes be traversed?*


## 1-5: 
### The knapsack problem is as follows: 
given a set of integers S = {s1, s2,...,sn},
and a target number T, find a subset of S which adds up exactly to T. For example,
there exists a subset within S = {1, 2, 5, 9, 10} that adds up to T = 22 but not
T = 23.
Find counterexamples to each of the following algorithms for the knapsack problem.
That is, giving an S and T such that the subset is selected using the algorithm does
not leave the knapsack completely full, even though such a solution exists.*

	(a) Put the elements of S in the knapsack in left to right order if they fit, i.e. the first-fit algorithm.
		A: let S = {1,7,9}, T = 10
	(b) Put the elements of S in the knapsack from smallest to largest, i.e. the best-fit algorithm.
		A: let S = {1,7,9}, T = 10
	(c) Put the elements of S in the knapsack from largest to smallest.	
		A: let S = {1,4,5,7,9}, T = 19

## 1-6:
### The set cover problem is as follows: 
*given a set of subsets S1, ..., Sm of the
universal set U = {1, ..., n}, find the smallest subset of subsets T ⊂ S such that   ????: does smallest mean least number of subsets? Least number of all elements?
∪ti∈T ti = U. For example, there are the following subsets, S1 = {1, 3, 5}, S2 =
{2, 4}, S3 = {1, 4}, and S4 = {2, 5} The set cover would then be S1 and S2.
Find a counterexample for the following algorithm: Select the largest subset for the
cover, and then delete all its elements from the universal set. Repeat by adding the
subset containing the largest number of uncovered elements until all are covered.*

	U = {1,2,3,4,5,6,7,8,9,10, 11}, S1 = {1,2,3,4,5}, S2 = {6,7,8,9}, S3 = {6,7,10}, S4 = {8,9,11}
	U` = {6,7,8,9,10,11}, T` = S1
	The Set with largest number of uncovered elements is S2. S3 and S4 must also be included in the set cover because they contain elements (10 & 11 respectivly)
	in U that are not members of any other subset. Therefore this algorithm gives us as the set cover all of the subsets, but S1 U S3 U S4 covers U and is smaller
	than S1 U S2 U S3 U S4
