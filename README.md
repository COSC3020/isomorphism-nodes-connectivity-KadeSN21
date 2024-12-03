# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

In order to prove that another completely connected graoh with the same number of nodes as $G1$ is isomorphic to $G1$, we need to find a "one-to-one" relationship between them, meaning that for every vertex $v1$ in $G1$, there is a vertex $v2$ in $G2$. We know that both graphs have the same number of vertices(nodes) $|V1| = |V2| = n$, so there is a one-to-one function that maps each vertex in $G1$ to a unique vertex in $G2$, therefore we can say that for two completely connected graphs $G1$ and $G2$ with the same number of nodes, there is a one-to-one function. However, this is not enough to prove that these are isomorphic, as there also needs to exist an "onto" function that ensures $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$. This means that every edge in $G1$ also needs to have a unique mapping in $G2$ that corespond with the mapped vertices. In a completely connected graph, all vertices are connected to eachother by an edge. For example, if we have a graph $G1$ with verticies $x,y,z$ the graph contains the edges $(x,y), (x,z), (y,z)$. If a graph $G2$ is also completely connected with vertices $a,b,c$, it too will have edges connecting all possible pairs of vertices, ie: $(a,b), (a,c), (b,c)$. This ensures that there can be a mapping between all vertices and edges in $G1$ and $G2$. For example we can map: $x \rightarrow a$, $y \rightarrow b$, $z \rightarrow c$, $(x,y) \rightarrow (a,b)$, $(x,z) \rightarrow (a,c)$, $(y,z) \rightarrow (b,c)$ This gives the bijection: $f: V_1 \rightarrow V_2$ such that $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$. Thus, all completely connected graphs with the sane number of nodes will be isomorphic to eachother.

help: To refresh my knowledge of complete graphs https://study.com/academy/lesson/complete-graph-definition-example.html, I also looked at lilybrongo's repo and your comments on their previouse attempts to get a better idea of what you were looking for.

“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”
