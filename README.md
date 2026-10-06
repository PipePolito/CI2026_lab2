Create 100 random instances of set-cover problem {S1, S2, ...., S100} and solve them by hill climbing

For each Sn:
- Objects in the universe: o_i with i [0, n-1]
- Family of sets: f_i with i [0, n -1 ]
- Each family f_i covers exacly i + 1 objects --> so f_0 covers 1 object and f_i-1 covers all objects
- With costs of 10 * U ~ [0, 1] + (f_i + U ~ [0, 1])²
- 