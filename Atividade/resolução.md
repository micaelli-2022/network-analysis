# RESPOSTAS

1. Define:

	**(a) Subgraph**
	
	Um Subgrafo é a parte de um grafo, ou seja, um Grafo A é subgrafo de B se o conjunto de vértice de A é um subconjunto   do conjunto de vértice de B, assim como, se o conjunto de arestas de A é um subconjunto do conjunto de arestas de B.
	
	**(b) Bipartite graph**
	
	São aqueles que podem ser divididos em dois conjuntos disjuntos A e B, onde toda aresta conecta um nó em A a um nó em B.
	
	**(c) Hamiltonian graph**
	
	Um grafo é hamiltoniano se ele possui um ciclo hamiltoniano, ou seja, passa por cada vértice uma única vez

	**(d) Eulerian graph**
	
	É um Grafo onde é possível caminhar por todas as suas arestas, visitando cada uma delas apenas uma vez. 

**2. Describe how a breadth-first search algorithm works**
<br>Primeiro começa pelo nó raiz e explora todos os seus nós vizinhos. E para cada um desses nós mais próximos explora seus nós vizinhos ainda não explorados. 

**3. How many edges does a complete graph with n vertices have? What about a complete directed graph with n vertices?**
<br>Um grafo completo tem n(n−1)/2 arestas
<br>Um grafo completo direcional tem n(n−1) arestas

**4. What are isomorphic graphs? Draw an example.**
<br>Os grafos G e H são isomórficos se houver uma estrutura que preserve uma correspondência biunívoca entre os vértices e arestas,ou seja, os dois grafos são estruturalmente equivalentes.

**5. Calculate the degree of the nodes for both node types in the bipartite adjacency matrix from the figure below. Find the isolated node(s).**

![adjacency matrix](./img/matrix01.png)

**6. Givenh`G = (V, E)` where `V = {M, N, O, P, Q, R, S}` and 
E ={(M, S), (N, O), (P, R), (N, S), (O, M),
 (N, Q), (O, M), (P, P), (S, M), (O, N), 
 (S, M), (N, R), (P, M), (M, S)}**

	**(a) Specify, if any, a simple path from vertex M to vertex S.**
	
	Não existe um caminho simples entre os vértices

	**(b) Specify, if any, a simple cycle, involving at least 4 nodes.**
	
	Não existe um ciclo simples com pelo menos 4 nós

	**(c) Is the digraph connected or not connected?**
	

	**(d) What is the degree of vertices N and R.**
	
	5 degree

	**(e) Represent the digraph using adjacency list representation.**
	
	**(f) Represent the digraph using adjacency matrix representation.**

**7. Draw the undirected and directed versions of the graph G(V, E), where V = {1, 2, 3, 4, 5, 6} and E = {(2, 5), (6, 1), (5, 3), (2, 3)}.**

**8. How many edges does a graph have 3 vertices of degree 3 and one vertex of degree 5?**

**9. Mr. A is friend with Mrs. B, but she doesn't like him back. She has a reciprocal friendship with both C and D, but only C considers D a friend. D has also sent friend requests to E, F, G, and H but, so far, only G replied. G also has a reciprocal relationship with A. Draw the corresponding directed graph.**

**10. Draw the graph from the previous exercise as undirected and weighted, with the weight being 2 if the connection is reciprocal, 1 otherwise.**
	
	
    (https://colab.research.google.com/drive/1SlGseEcN8AG-Acb21OcxCf0n7W-zjIQJ?usp=sharing)
