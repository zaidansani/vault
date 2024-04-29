---
publish: true
title: Weighted Union
---

| object | .... |
| ------ | ---- |
| parent | .... |
| size   | .... |
1. The augmentation makes sure the trees are as balanced
2. Searching will be on a balanced tree
3. The maximum depth $h = log(n)$.

# ``find(p)``

> [!info] Objects are connected if they are of the same tree

$$ O(log(n))$$
1. Find highest parent of $p$
2. Find highest parent of $q$
3. If highest parent of $p$ and $q$ are the same, objects are connected.

# ``union(p, q)``


$$ O(log(n)) $$
1. Find highest parent of $p$
2. Find highest parent of $q$
3. If the size of the highest parent of $p$ is more than the highest parent of $q$,
	1. Change the parent of the highest parent of $q$ to the highest parent of $p$.
4. Else, do the reverse.
	1. Change parent of highest parent of $p$ to highest parent of $q$.

# Augmentation
Adding [[Path Compression]] allows for even faster time.