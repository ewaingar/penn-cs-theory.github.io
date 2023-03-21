---
title: "Theory Seminar: Zihan Tan"
date: 2023-03-24
---

The theory seminar is back in Levine 307 this Friday 3/24 at 1PM, featuring Zihan Tan from Rutgers University.

**Title:** A Subpolynomial Approximation Algorithm for Graph Crossing Number in Low-Degree
Graphs

**Abstract:** Graph Crossing Number is a fundamental and extensively studied problem with
wide ranging applications. In this problem, the goal is to draw an input graph G in the plane
so as to minimize the number of crossings between the images of its edges. The problem is
notoriously difficult, and despite extensive work, non-trivial approximation algorithms are only
known for bounded-degree graphs. Even for this special case, the best current algorithm
achieves a -approximation, while the best current negative results do not rule out constant-
factor approximation. All current approximation algorithms for the problem build on the same
paradigm, which is also used in practice: compute a set E’of edges (called a planarizing set)
such that G \ E’ is planar; compute a planar drawing of G \ E’; then add the drawings of the
edges of E to the resulting drawing. Unfortunately, there are examples of graphs G, in which
any implementation of this method must incur Ω(OPT 2 ) crossings, where OPT is the value of
the optimal solution. This barrier seems to doom the only currently known approach to
designing approximation algorithms for the problem, and to prevent it from yielding a better
than -approximation.

We propose a new paradigm that allows us to overcome this barrier. Using the new paradigm,
we reduce the Crossing Number problem to Crossing Number with Rotation System – a
variant of the Crossing Number problem, in which the ordering of the edges incident to every
vertex is fixed as part of input. We then show a randomized algorithm for this new problem,
that allows us to obtain a subpolynomial approximation for Graph Crossing Number on low-
degree graphs.

This talk is based on joint work with Julia Chuzhoy and Sepideh Mahabadi.
