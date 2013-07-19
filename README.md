NetX_matlab
===========
* A: deterministic
* P: probabilistic
* K: Kronecker core

* [A P] = grandom(n_size [, density=0.5])
* [A P] = gkronecker(K, p [, n_size=power(ksize,p)])

* [A] = gsample(P)
* [A] = gload(filename [, n_size])

* [C] = kronecker(A, B)
* [Pow] = kpow(A, k)

* issym(A)
* isdigraph(A)
* isupper(A)
* islower(A)

* [centra] = ceigenvector(A [, scaling]);

// drawing
* draw_circle(A)

* [xcdf ycdf] = cdf_rank(list,'on');

[Digraph A]
* \#edges = sum(sum(A));
* \#indegs = sum(A)
* \#outdegs = sum(A,2)
* \#totaldegs = \#indegs + \#outdegs

