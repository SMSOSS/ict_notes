# M2311 #
- Max amount of subarray that gcd <= k
- Observation : GCD keep decrease/remain unchanged
- Large query -> Pre-compute!
- Binary search until gcd <= k
- Partial sum to store gcd

# M2312 #
- Use map to store (No 2d array)
- Observation : How to detect loop ? -> Mark if visited / check run how many
- Path compression : Mark down end pt -> skipppp
- if update -> dsu to maintain (+compression)
- dsu : head = end pt 
- Infinite -> Init dsu itself , have value -> map!
- Handle Ice -> separate 4
- How to escape loop ? -> dsu union both connected  -> mark the pos -> if enter dsu than -1

# M2313 #
- Pattern Observation -> Get first 2 subtask
- Didn't attend morning session so can't understans :(
- Exhaust GCD -> connect multiple (4 , 8..)

# M2314 #
- Easiest question (by trainer)
- Largest = itself , smallest = combine all 
- Start from left (More significant) 
- think as DP(?)
