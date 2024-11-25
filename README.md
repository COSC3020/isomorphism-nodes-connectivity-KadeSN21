# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

We know that for two complete graphs to be isomorphic they must have: the same number of verticies, the same number of edges, the same degree sequence, as well as the same structure. Having a completely connected graph means that for every pair of verticies, we have a unique edge that connects each of those pairs. Being that both graphs $A$ and $B$ have $n$ verticies, they are identical in number of verticies, this satisfies the bijection: $f: V_1 \rightarrow V_2$. They both also are composed of $(n(n-1))/2$ edges, this tells us that the number of edges for graphs $A$ and $B$ are also identical. We know that a complete graph the degree sequence of each verticy is $n-1$ ($n-1$ edges connecting to each verticy), because the number of verticies are the same for graphs $A$ and $B$, the number of edges per verticy(degree) will also equal eachother. ie: the degree sequence of both $A$ and $B$ will be [$n-1, n-1, n-1$] for all $n$ verticies. Because these graphs have an identical adjacency matrix(a matrix showing what vertecies connect to eachother), it is apparent that they have the same structure. With this, we can map any vertex in graph $A$ to any vertex in graph $B$ and fulfill the case that there exists a one-to-one and bijection when doing so. Thus, and two completely connected graphs with the same number of nodes(vertecies) must be isomorphic.

help: To refresh my knowledge of complete graphs https://study.com/academy/lesson/complete-graph-definition-example.html

“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”
