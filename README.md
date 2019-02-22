# Difficult graphs for practical graph isomorphism solvers
These graphs are based on the construction proposed by my supervisor
Anuj Dawar in this paper:

https://arxiv.org/abs/1809.08154

It essentially takes a random 3-XOR Formula, converts it into a graph,
and applies the multipede construction using the the Cai Fürer Immerman gadget.

The construction contains a random component, so graphs produced with the 
same parameters will be different and have varying solve times. The
graphs I have attached in dreadnaut and DIMACS format are from a single
pass, and I can produce more difficult graphs of that size by retrying.

I have also included the solve times, which I obtained from running the
graphs on the Cambridge High Performance Cluster:

https://www.cl.cam.ac.uk/local/sys/resources/hpc/
