## Computational Complexity

Appendix

- Set
  - e.g. N = {1,2,3}
  - [n] = {1,2,3,…,n}
  - |A| = number of element in A
- Function
  - e.g. f: A -> B, function f from set A -> B
  - $|A|^{|B|}$ =number of possible functions from B -> A
  - one-to-one if every input give unique output, A -> B (injective)
    - if  A and B are finite then |A| <= |B|
  - onto if every element y in B there exists x in A such that f(x) = y, (surjective)
  - permutation if onto and one-to-one (bijective)
    - permutation implies |A| = |B|
- Pair and tuple
  - A x B denote the set of all ordered (?) pair <a, b> with a in A, b in B
  - if finite then |A x B| = |A| x |B|
  - $A^n$ for AxAxA…. (n times)
  - $\{{0, 1}\}^n$ bits of length n
  - \* is n >= 0
  - n=0 contains single element empty word E
- Graph
  - is {u, v}, u = edges, v = vertices
  - neighbor of v are all u in V such that uv in V
  - directed graph is <u,v>, sometimes $\underset{uv}{\rightarrow}$
  - adjacency matrix denote all pairs of uv, 1 if connected else 0
    - undirected graph are symmetric
- Boolean
  - true false
  - and = ^
  - or = $\or$
  - not = $\neg$
  - $\{TRUE, FALSE\}^n$ = $\{{0, 1}\}^n$
  - $\oplus$ is xor
  - if ' is formula then '(u) means the formula's variable is assigned to values in u, boolean values
    - satisfiable if there is '(u) = true
- Quantifier
  - for all: $\forall$
  - exists: $\exist$
- Probability Space
  - $\Omega\{\omega_1,\dots,\omega_n\}$ where each $w$ has probability of $p$ being selected when chose randomly. If no $p$ (distribution)  specified we use the normal distribution.
- Averaging Argument
  - If a1, a2, …, an are some numbers whose average is c then some ai ≥ c.
    - Similarly if E[X] = u then the event e >= u has non-zero probability
    - (Markov's inequality) Any nonnegative random variable X satisfies Pr(X >= k E[X]) <= 1/k
