# Compressed sensing - Semidefinite Relaxations for Integer Programming

Authors : Rémy Deshayes and Éric Lavergne

Our project is based on the work of Franz Rendl in _Semidefinite Relaxations for Integer Programming_. We summarized the main ideas of the article and implemented some of the solutions described in the survey for the two classical problems of maxcut and graph coloring.

The first part _1. Approachs for Integer Programming_ quickly introduces the approaches used in this field. The second part _2. The basics of Semi Definite Optimization_ outlines the main ideas of SDP programming. The third part _3. Famous COP, SDP relaxation and hyperplane rounding_ considers the examples of two classical problems, Max-Cut and Graph coloring, that can be solved thanks to SDP programming. Once a solution of the SDP relaxation has been obtained, the hyperplane rounding algorithm is used to obtain a good solution in the initial space. Finally, in the last part _4. Interior Points methods for SDP programming and more_, we describe methods to compute SDP problems.
