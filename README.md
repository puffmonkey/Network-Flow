# Network-Flow

In combinatorial optimization, network flow problems are a class of computational problems in which the input is a flow network (a graph with numerical capacities on its edges), and the goal is to construct a flow, numerical values on each edge that respect the capacity constraints and that have incoming flow equal to outgoing flow at all vertices except for certain designated terminals.

Specific types of network flow problems include:

The maximum flow problem, in which the goal is to maximize the total amount of flow out of the source terminals and into the sink terminals
The minimum-cost flow problem, in which the edges have costs as well as capacities and the goal is to achieve a given amount of flow (or a maximum flow) that has the minimum possible cost
The multi-commodity flow problem, in which one must construct multiple flows for different commodities whose total flow amounts together respect the capacities
Nowhere-zero flow, a type of flow studied in combinatorics in which the flow amounts are restricted to a finite set of nonzero values
The max-flow min-cut theorem equates the value of a maximum flow to the value of a minimum cut, a partition of the vertices of the flow network that minimizes the total capacity of edges crossing from one side of the partition to the other. Approximate max-flow min-cut theorems provide an extension of this result to multi-commodity flow problems. The Gomory–Hu tree of an undirected flow network provides a concise representation of all minimum cuts between different pairs of terminal vertices.

Algorithms for constructing flows include

Dinic's algorithm, a strongly polynomial algorithm for maximum flow
The Edmonds–Karp algorithm, a faster strongly polynomial algorithm for maximum flow
The Ford–Fulkerson algorithm, a greedy algorithm for maximum flow that is not in general strongly polynomial
The network simplex algorithm, a method based on linear programming but specialized for network flow
The out-of-kilter algorithm for minimum-cost flow
The push–relabel maximum flow algorithm, one of the most efficient known techniques for maximum flow

# INF4130 - Algorithm design and Efficiency
Network flow was a mandatory assignment as part of the course INF4130 - Algorithm Design and Efficiency at the University of Oslo. As part of the course, one goes through general algorithm classes such as dynamic programming, heuristic algorithms, probabilistic algorithms and more. The main focus of the course was on the efficiency of the solutions done in the mandatory assignments and understanding the theory for NP-completeness to better understand what problems can be solved within feasible time and others which are intractable.

# Learning outcome

 - Edmonds–Karp algorithm
 - Ford–Fulkerson algorithm
 - Maximum flow
 - Minimum-cost
 - Graph theory
 - Network flow
