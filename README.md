### Online Supplement of

# Finding Minimum Balanced Separators - an Exact Approach

#### Ralf Borndörfer, Stephan Schwartz, and William Surau

Zuse Institute Berlin, Takustr 7, 14195 Berlin

---

This online supplement provides detailed results of the computational experiments conducted for the paper "Finding Minimum Balanced Separators - an Exact Approach". A preprint is available as [technical report](https://opus4.kobv.de/opus4-zib/frontdoor/index/index/docId/) published by Zuse Institute Berlin, 2021.

## Instances
For the computational study, we use two types of random transit networks: random trees, and random networks based on Voronoi diagrams.
The original transit networks as well as the line graph (labelled with "_lg") versions are provided in a [GitHub repository](https://github.com/stephanschwartz/vertex_covering_with_capacitated_trees/tree/main/instances). The instances are generated with our [transit network generator](https://github.com/stephanschwartz/transit_network_generator).
Since the original transit networks are edge weighted we only run our experiments on the line graphs.

## Detailed Results
We present detailed results of our computational study for all instances. In particular we report on the following outputs that are explained in the paper.

* instance properties:

   - number of nodes
   - number of edges
   - treewidth

Computation times for

  - row generation algorithm
  - compact MIP formulation

For the computation times, a time limit of 2 hours (i.e., 7200 seconds) was set.
