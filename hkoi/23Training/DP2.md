# DAG #
- Apply with topological sort to determine the DP order
- Using stack : Pick one node -> DFS -> no more move than put into oder
- Using set : indegree = 0 -> neighbour indegree -1 -> if indeg = 0 do 

## Usage1 - Number of paths ##
- Let path(x) be number of paths from A to X
- path(x) = path(1) + path(2) + ... path(x)

# Tree # 
- Root Leaf / Parent Child / Ancestor Descendent / Height Depth / Subtree

## Subtree size ##
- DFS each node -> O(n^2)
- DP : dp[i] = size of subtree 1 -> dp[i] = 1+ dp[j] (j is child) -> O(n)

## Painter ## 
- rooted binary tree with size N
- each node 3 dp stat ( 0: painter 1: covered by child 2: not covered!)
```
dp[i][0] = 1 + dp[j][2] + dp[k][2]
dp[i][1] = min(dp[j][0] + dp[k][1] , dp[j][1]+dp[k][0] 
dp[i][2] = dp[j][1] + dp[k][1]
```

## Path Passing through ##
- sz[i] = size of subtree
- ans += sz[this subtree] + sum(sz[other subtree]) -> ans/2 
- O(n)

# Bitwise DP #
- Use bitmask -> 0/1 represent take/no take 

# Memory optimization - Rolling array ##
- Optimization on memory suage -> avoid saving data that no longer useful
- Count number of ways in N*M grid -> memory complexity O(NM)
  - only dp[i-1][1...M] is needed for finding dp[i] -> keep 2 rows instead! -> memory complexity O(M)
  -
