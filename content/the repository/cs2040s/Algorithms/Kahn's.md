---
publish: true
title: "Kahn's"
---
1. Add all nodes with in-degree $0$ to queue.
2. For each outgoing edge from removed node, decrement in-degree of destination node by $1$.
3. If in-degree of destination node becomes $0$, add to queue.