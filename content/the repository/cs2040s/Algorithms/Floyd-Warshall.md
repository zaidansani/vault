[Dynamic Programming](../Paradigms/Dynamic%20Programming.md)
# Subproblems
Let $S[v, w, P]$ be the shortest path from $v$ to $w$ that only uses intermediate nodes in the set $P$.

$S[v, w, P_k]= min( S[v, w, P_{k-1}], S[v, x, P_{k-1}] + S[x, w, P_{k-1}])$
