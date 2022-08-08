# Independant Set System
Created: 2022-07-18 13:57

Set system $(E,\mathcal{F} \subset 2^E)$ called Independant Set System(ISS) if:
1. $\varnothing \in \mathcal{F}$
2. if $X \subseteq Y \in \mathcal{F}$, then $X \in \mathcal{F}$



Let there be some $c: E \rightarrow \mathbb{R}$ What we can do:
1. Find Set $A \in ISS:\; c(A)=\sum\limits_{a \in A}c(a) \rightarrow max$
	- Good example: [Kruskal's algorithm](https://en.wikipedia.org/wiki/Kruskal%27s_algorithm) for finding minimum spanning tree, so we can apply Greedy algorithm
	- Bad example: Bipartite matching, it satisfies ISS rules, but we can not apply Greedy algorithm here
2. Find Base $B:\; c(B) \rightarrow min$


### See also
[[Matroid]]

## References
1. [[ISSandMatroid.pdf]]
2. [[vygen_english.pdf#page=312]]
3. [ИТМО](https://youtu.be/7hu0tlWDvsY)