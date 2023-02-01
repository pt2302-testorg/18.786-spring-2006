---
content_type: page
description: Study materials section contains the questions asked as a virtual office
  hours.
learning_resource_types: []
ocw_type: CourseSection
title: Study Materials
uid: b4df34bc-ddc2-4eef-9275-5daad8d58f9c
---

Virtual Office Hours
--------------------

This "virtual office hours" is meant to record answers to questions asked either in person or by email, including questions about homework provided in the {{% resource_link fa330eea-0238-bbad-1d99-2dd9f6a9b0fa "assignments" %}} section.

Question: If R is an integrally closed domain, why is R\[x\] integrally closed? (Problem Set 2, problem 2a)  
Answer: Helpful hints:

*   Let K be the fraction field of R: use "transitivity of integral closure" to reduce to checking that R\[x\] is integrally closed in K\[x\].
*   Show that if f, g in K\[x\] are monic and fg is in R\[x\], then f and g are both in R\[x\]. (Hint: pass from K to a splitting field for fg.)
*   Handy trick: given f in K\[x\] satisfying an integrality relation over R\[x\] of some degree, then f + x^n satisfies an integrality relation of the same degree. Take n "large" and write the constant term of the new relation as (f+x^n) times (something else forced to be monic).

Question: How do I get started thinking about Problem Set 2, problem 6? (Related question: Problem Set 2, problem 2b.)  
Answer: Try thinking about the ideal (x^2,y) in the ring C\[x,y\]\_{(x,y)}: the point is that it is not a power of the maximal ideal M, because it is sandwiched between M and M^2.

Question: Let K be a number field. How do I compute its ring of integers R? (Problem Set 2, problem 3)  
Answer: For individual elements of a number field, a good way to test integrality is to compute the minimal polynomial. This may however come out messy when you try to do it with coefficients (e.g., if you try to compute the minimal polynomial of a + b 2^(1/3) + c 2^(2/3) as a polynomial in a, b, c). It may be easier to use the following two facts:

*   Let b\_1, ..., b\_n be a basis of K over Q consisting of elements of R. Then R is contained in the Z-span of the dual basis of b\_1, ..., b\_n for the dual pairing. (See Janusz I.6 or the notes from Lec #5.)
*   R is a ring! That's actually surprisingly useful once you account for the previous item: for instance, if you have something in the Z-span of the dual basis, but its square is not in the span, it can't be in R.

Question: If p,q are primes congruent to 1 modulo 4, how do I find an element of the class group of Q(sqrt(-pq)) of order 2? (Problem Set 5, problem 5a)  
Answer: Construct a rational prime which splits as a product of two primes, but which is not the absolute norm of an element of the ring of integers. (You'll end up using some congruence conditions, and quadratic reciprocity. Oh, and Dirichlet's theorem on primes in arithmetic progressions.) Then each of the two primes lying above is nonprincipal; if you set this up right, the same argument will show that no odd power of these primes is principal either.

Question: How do I prove that any automorphism of Q\_p is continuous (and hence trivial)? (Problem Set 7, problem 9(a))  
Answer: One approach is to prove that the set of elements of Q\_p^\* which have n-th roots for all n coprime to p is a neighborhood of 1. (Hint: analyze convergence of the binomial series.)

Question: Is it really true that a formal power series over Q\_p and its derivative have the same radius of convergence? Doesn't the sum x^{p^n} give a counterexample? (Problem Set 8, problem 3)  
Answer: It's really true, as long as you remember that radius of convergence should be defined using the usual calculus formula. The point is that it tells you about convergence when you plug in values of x which lie in **extensions** of Q\_p, not just Q\_p itself; that in particular gives you a "nondiscrete" set of absolute values that x can take on.

Question: I've convinced myself that every totally tamely ramified extension of a finite extension K of Q\_p has the form K(pi^{1/d}), where pi is some uniformizer. How do I use this to show that Q\_p(zeta\_p) = Q\_p((-p)^{1/(p-1)})? (Problem Set 9, problem 7)  
Answer: Check that (1-zeta\_p)^(p-1)/(-p) is a (p-1)-st power in Q\_p(zeta\_p). This amounts to checking that it has image 1 in the residue field, and then verifying (using a binomial series) that any element of Z\_p\[zeta\_p\] which is congruent to 1 modulo 1-zeta\_p is a (p-1)-st power.

Question: If K is a field of characteristic coprime to n, L = K(zeta\_n), and M = L(a^{1/n}) is a Kummer extension, when is M Galois over K? (Problem Set 10, problem 5(b))  
Answer: If and only if every conjugate of a has the form a^m x^n for some integer m coprime to n.

Question: On problem 3 of the final, I have this power series that converges in a certain radius. But how do I know that the limit is actually equal to the rational function that it's formally supposed to be equal to?  
Answer: Because you can check that equality after multiplying by the **value** of the denominator at any particular point in the domain of convergence. Once you've done that, you can formally manipulate the side with the power series times the denominator to convert it into the numerator.