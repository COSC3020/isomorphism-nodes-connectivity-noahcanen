# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Let's start with the definition of a connected graph. A connected graph is a graph where each vertex is connected to every other vertex by an edge.


This means that a graph with N nodes has n(n – 1)/2 edges. Or that each node has ( n-1) edges connected to it.


This means that as long as the two graphs have the same number of nodes, the two completed graphs will have the same number of edges. And all the nodes will have the same number of edges connected to them.


This means that any node can be mapped to any other node because all the nodes have the same number of edges. Since there are only N nodes in both graphs, each node can be mapped onto an equivalent node inside the other graph, making a one-to-one function.


This means that each node in one of the two graphs is mapped to exactly one node in the other, creating an onto function. 


Meaning that there is a one-to-one and onto function between two complete graphs with the same number of nodes, and they are completely connected. So two graphs that have the same number of nodes and are completely connected are isomorphic.


For this assignment, I used the resource of https://en.wikipedia.org/wiki/Complete_graph

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."



