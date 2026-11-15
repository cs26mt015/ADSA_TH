**Unit 1: Computational Problems and Complexity**
1. Computational Problems
- Decidable and undecidable problems
- Decision problems
- Optimization problems
- Minimization and maximization problems
- Polynomial-time algorithms
- Exponential-time algorithms
2. Complexity Classes
- Class P
- Class NP
- Deterministic and nondeterministic algorithms
- Polynomial-time verification
- Certificates and witnesses
- Relationship between P and NP
- NP-complete problems
- NP-hard problems
- Relationship between NP-hard and NP-complete
3. Polynomial-Time Reductions
- Definition of polynomial-time reduction
- Reduction between decision problems
- Yes-instance and No-instance preservation
- Reduction direction
- Transitivity of reductions
- Proving NP-hardness using reductions
- Proving NP-completeness

**Unit 2: NP-Completeness and Reductions**
4. Boolean Satisfiability Problems
- Boolean variables and literals
- Boolean formulas
- Satisfiability
- Circuit-SAT
- Reduction from Circuit-SAT to SAT
- Conjunctive Normal Form (CNF)
- 3-CNF-SAT
- Reduction from SAT to 3-CNF-SAT
5. Hamiltonian Cycle
- Definition of Hamiltonian path
- Definition of Hamiltonian cycle
- Difference between Hamiltonian and Eulerian paths
- Hamiltonian Cycle decision problem
- Adjacency matrix representation
- Backtracking approach
- NP-completeness proof
6. Clique Problem
- Complete graph
- Clique and clique size
- Clique decision problem
- Maximum Clique optimization problem
- Reduction from 3-SAT to Clique
- NP-completeness proof
7. Independent Set
- Definition of independent set
- Independent Set decision problem
- Maximum Independent Set
- Reduction from Clique to Independent Set
- Complement graph
- Relationship between Clique and Independent Set
8. Vertex Cover
- Definition of vertex cover
- Vertex Cover decision problem
- Minimum Vertex Cover
- Relationship between Independent Set and Vertex Cover
- Reduction from Independent Set to Vertex Cover
- Proof of the relationship
9. Dominating Independent Set
- Independent set
- Dominating set
- Dominating Independent Set
- Conditions for a dominating independent set
- Decision problem
- Relationship between independence and domination
10. Balanced Biclique
- Bipartite graphs
- Complete bipartite graphs
- Balanced biclique
- Biclique decision problem
- Verification of a biclique
- NP-completeness proof
11. Half Clique
- Clique
- Half-clique definition
- Decision problem
- Relationship with ordinary Clique
- Reduction-based proof
12. Subset Sum
- Problem definition
- Decision version of Subset Sum
- Dynamic programming approach
- DP state definition
- Recurrence relation
- Base cases
- Complexity analysis
- NP-completeness proof using 3-SAT reduction

**Unit 3: Graph Algorithms**
13. Hamiltonian Cycle Algorithm
- Adjacency matrix
- Path construction
- Candidate vertex selection
- Validity checking
- Backtracking
- Termination condition
- Time complexity
14. Eulerian Path and Circuit
- Eulerian path
- Eulerian circuit
- Difference between Hamiltonian and Eulerian problems
- Conditions for Eulerian circuit
- Conditions for Eulerian path
- Fleury's algorithm
- Bridge detection
- Step-by-step construction

**Unit 4: Dynamic Programming**
15. Matrix Chain Multiplication
- Matrix dimensions
- Matrix multiplication cost
- Parenthesization
- DP state
- Recurrence relation
- Base cases
- Optimal split position
- Construction of optimal parenthesization
- Time and space complexity
16. Optimal Binary Search Tree
- Successful search probabilities \(p_i\)
- Unsuccessful search probabilities \(q_i\)
- Expected search cost
- Root selection
- DP cost table
- Weight table
- Root table
- Recurrence relation
- Construction of optimal BST
- Worked examples
17. Rod Cutting
- Rod length and price table
- Maximum revenue
- Recursive formulation
- DP formulation
- Cutting decisions
- Reconstructing the optimal cuts
- Time and space complexity

**Unit 5: Tree Decomposition**
18. Path Decomposition
- Definition of a path decomposition
- Bags and vertices
- Vertex coverage condition
- Edge coverage condition
- Connectedness condition
- Width of a path decomposition
- Pathwidth
- Separation
- Examples of valid and invalid decompositions
19. Tree Decomposition
- Definition of tree decomposition
- Bags and tree structure
- Vertex coverage
- Edge coverage
- Connectedness property
- Width of a tree decomposition
- Treewidth
- Relationship between pathwidth and treewidth
20. Nice Tree Decomposition
- Definition and purpose
- Leaf node
- Introduce node
- Forget node
- Join node
- Conversion to nice tree decomposition
- Empty root and leaf conventions
- Advantages for dynamic programming

**Unit 6: Binary Search Trees**
21. Binary Search Tree (BST)
- Definition and properties
- BST ordering property
- Tree structure and node representation
- Searching
- Recursive search
- Iterative search
- Insertion
- Deletion
  - Node with no children
  - Node with one child
  - Node with two children
- Inorder successor
- Inorder predecessor
- Minimum and maximum elements
- Inorder traversal
- Best, average and worst-case complexity
- Skewed BST

**Unit 7: Red-Black Trees**
22. Red-Black Tree Properties
- Red and black nodes
- Root property
- NIL leaves
- Red-parent rule
- Equal black-height property
- Black height
- Longest and shortest paths
23. Rotations
- Left rotation
- Right rotation
- Rotation properties
- Maintaining BST ordering after rotation
24. Height Analysis
- Internal nodes and subtree size
- Black-height relationship
- Proof of minimum subtree size
- Proof that height is logarithmic
- Bound on Red-Black Tree height
25. Insertion
- BST insertion
- New node coloring
- Violation of Red-Black properties
- Recoloring
- Left and right rotations
- Insertion fix-up cases
- Correctness of insertion
26. Deletion
- BST deletion
- Replacement node
- Successor-based deletion
- Double-black situation
- Deletion fix-up cases
- Recoloring and rotations
- Correctness of deletion

**Unit 8: Order Statistics and Augmented Data Structures**
27. Order Statistics
- Meaning of order statistics
- \(i\)-th smallest element
- Minimum and maximum
- Median
- Selection problem
- Quickselect
- Median of Medians
- Grouping elements into groups of five
- Finding the median of medians
- Partitioning
- Worst-case linear-time selection
28. Augmented Binary Search Trees
- Meaning of data structure augmentation
- Storing additional information in nodes
- Subtree size
- Updating subtree information
- Augmented BST construction
- Searching using augmented information
- Complexity analysis
29. Order-Statistic Trees
- Subtree-size field
- Maintaining subtree size during insertion
- Maintaining subtree size during deletion
- OS-Select
- Finding the \(i\)-th smallest element
- OS-Rank
- Finding the rank of a given element
- Complexity in balanced and unbalanced BSTs

**Unit 9: B-Trees**
30. B-Tree Properties
- Definition of a B-Tree
- Minimum degree
- Maximum and minimum number of keys
- Maximum and minimum number of children
- Root properties
- Leaf properties
- All leaves at the same depth
- Height of a B-Tree
31. B-Tree Operations
- Searching
- Insertion
- Full-node detection
- Node splitting
- Splitting the root
- Splitting a child node
- Promoting the median key
- Recursive insertion
- Maintaining B-Tree properties
