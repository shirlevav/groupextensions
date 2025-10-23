# Computing Group Extensions in GAP4
These functions in GAP compute polycyclic group extensions in two different ways. 

The representative method implementation requires inputs of polycyclic groups G, N and a record of a homomorphism Aut(N)->Out(N) and a coupling G->Out(N). It verifies if the given coupling is induced by an extension of G by N, and if so, computes one group extension corresponding to this coupling. 

The iterative method implementation requires inputs of groups polycyclic G, N and a record of a homomorphism Aut(N)->Out(N) and a coupling G->Out(N). It computes a representative of all equivalence classes of G by N that induce the given coupling, but is inefficient in many cases.
