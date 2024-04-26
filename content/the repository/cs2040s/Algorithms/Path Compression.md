After finding the root of the tree (the highest parent), set parent of each traversed node to the root.

# `findRoot(p)`

1. Find the root of $p$
2. From $p$, backtrack all the way to root of $p$ while changing the parent of all nodes to the root of $p$.