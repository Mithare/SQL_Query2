# SQL_Query2

A ski resort company is planning to construct a new ski slope using a pre-existing network of mountain huts and trails between them.
A new slope has to begin at one of the mountain huts, have a middle station at another hut connected with the first one by a direct trail,
and end at the third mountain hut which is also connected by a direct trail to the second hut. The altitude of the three huts chosen for 
constructing the ski slope has to be strictly decreasing.
You are given two SQL tables, mountain_huts and trails, with the following structure.
Each entry in the table trails represents a direct connection between huts with IDs hut1 and hut2. Note that all trails are bidirectional.
Create a query that finds all triplets(startpt,middlept,endpt) representing the mountain huts that may be used for construction of a ski slope.
Output returned by the query can be ordered in any way.
