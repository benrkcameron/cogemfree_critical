# cogemfree_critical
collection of co-gem-free (the co-gem is the graph on 5 vertices consisting of 4-vertex path and an isolated vertex) vertex-critical graph files in graph6 format

Currently contains all 5-vertex-critical co-gem-free graphs up to order at most 18 using the program CriticalPfreeGraphs by Jan Goedgebeur available here: https://caagt.ugent.be/criticalpfree/

Note that there are 327 graphs total and the largest order is order 12, so no such graphs exist of order 13-18. Here is the output of the program (other than the actual graphs):


./critical_Pfree_graphs 18 c4 P4 P1 vertexcritical\n
32 bit mode
Info: only outputting graphs which are NOT 4-colourable
Info: only outputting graphs with no induced P4's
Info: outputting vertex critical graphs
Program for outputting 5-critical P4-free graphs
Actually only outputting (P4+P1)-free graphs!
Info: NUM_PREV_SETS: 20
Info: LEVEL_LEAST_CHILDREN: 32
Info: only outputting k-vertex-critical graphs
./critical_Pfree_graphs 18 c4 P4 P1 vertexcritical
Info: writing K5
Info: starting construction from C5
Info: starting construction from C7
Info: starting construction from C9
Info: starting construction from C11
Info: starting construction from C13
Info: starting construction from C15
Info: starting construction from C17
Info: starting construction from antihole C7 (chromatic number: 4)
Info: starting construction from antihole C9 (chromatic number: 5)
Nv=8, times P-free: 1463 (67.92%)
Nv=9, times P-free: 20127 (49.69%)
Nv=10, times P-free: 161881 (22.87%)
Nv=11, times P-free: 581792 (7.52%)
Nv=12, times P-free: 1435465 (2.66%)
Nv=13, times P-free: 2733821 (1.07%)
Nv=14, times P-free: 4577015 (0.50%)
Nv=15, times P-free: 6936037 (0.24%)
Nv=16, times P-free: 9644799 (0.12%)
Nv=17, times P-free: 12984270 (0.06%)
Nv=18, times P-free: 17240393 (0.03%)
Nv=10, times no lemmas applicable: 452
Nv=11, times no lemmas applicable: 161
Nv=12, times no lemmas applicable: 6
Nv=13, times no lemmas applicable: 0
Nv=14, times no lemmas applicable: 1
Nv=15, times no lemmas applicable: 0
Nv=16, times no lemmas applicable: 0
Nv=17, times no lemmas applicable: 0
Nv=5, num non-iso graphs gen: 1 (incl. iso: 1), noniso: 100.00%
Nv=6, num non-iso graphs gen: 6 (incl. iso: 15), noniso: 40.00%
Nv=7, num non-iso graphs gen: 49 (incl. iso: 113), noniso: 43.36%
Nv=8, num non-iso graphs gen: 491 (incl. iso: 1416), noniso: 34.68%
Nv=9, num non-iso graphs gen: 5462 (incl. iso: 18443), noniso: 29.62%
Nv=10, num non-iso graphs gen: 47787 (incl. iso: 120728), noniso: 39.58%
Nv=11, num non-iso graphs gen: 220373 (incl. iso: 367235), noniso: 60.01%
Nv=12, num non-iso graphs gen: 644759 (incl. iso: 864603), noniso: 74.57%
Nv=13, num non-iso graphs gen: 1356564 (incl. iso: 1622208), noniso: 83.62%
Nv=14, num non-iso graphs gen: 2440682 (incl. iso: 2845922), noniso: 85.76%
Nv=15, num non-iso graphs gen: 3821533 (incl. iso: 4459858), noniso: 85.69%
Nv=16, num non-iso graphs gen: 5559340 (incl. iso: 6554951), noniso: 84.81%
Nv=17, num non-iso graphs gen: 7795539 (incl. iso: 9274065), noniso: 84.06%
Nv=18, num non-iso graphs gen: 10774304 (incl. iso: 12843975), noniso: 83.89%
Number of vertex-critical graphs written: 327
CPU time: 122773.0 seconds.

