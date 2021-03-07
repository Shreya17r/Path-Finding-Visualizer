# Path-Finding-Visualizer
## Path finder using A star Algorithm

A* Algorithm is one of the most successful search algorithms to find shortest path between nodes and graphs.

We were recently taught this algorithm in my credit course of Artificial Intelligence.
From what I learned, A* algorithm is an informed search algorithm. It uses information on path cost and heuristics to find the solution. 

A* equals <b>optimality</b> and <b>completeness</b>.

### What is heuristics?

"A heuristic function, also called simply a heuristic, is a function that ranks alternatives in search algorithms at each branching step based on available information to decide which branch to follow. For example, it may approximate the exact solution.."

<ul>
  <li>g(n) — this represents the exact cost of the path from the starting node to any node n.</li>
  <li>h(n) — this represents the heuristic estimated cost from node n to the goal node.</li>
  <li>f(n) — lowest cost in the neighboring node .</li>
  </ul>  
Each time A* enters a node, it calculates the cost, f(n)(n being the neighboring node), to travel to all of the neighboring nodes, and then enters the node with the lowest value of f(n).
These values we calculate using the following formula:

f(n) = g(n) + h(n)

## Output:

<img src="https://i.imgur.com/e9EPDaO.gif"/>




