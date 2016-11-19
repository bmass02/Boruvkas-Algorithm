# Boruvkas-Algorithm
This is code created by Sreyas Rangaraju for CECS 620 as a tool to solve MST problem using Boruvka's Algorithm.

<h2>Input</h2>
Input is taken from inside the program. To change the problem instance, open the python file and set "adjMatrix" to
the specifications of the problem instance. Input is in the form of an array of arrays. The indices of the outside
array represent the vertices and the values in the inner arrays represent edge costs to the vertice represent by the
indice of the value.
<h3>Example</h3>
<code>adjMatrix = [[0,9,75,0,0],[9,0,95,19,42],[75,95,0,51,0],[0,19,51,0,31],[0,42,0,31,0]]</code>
Vertices: 0, 1, 2, 3, and 4
Edges(cost): [0,1](9), [0,2](75), [1,0](9), [1,2](95), etc.

Feel free to use and/or modify this code.
