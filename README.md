# Git Practice
A simple project to practice a few git/github workflows.  Replace the contents of this file with the contents indicated in the [instructions](./instructions.md).



# Graph Coverage and Test Path Optimization

## Resources
- [Graph Coverage](https://cs.gmu.edu:8443/offutt/coverage/GraphCoverage)
- [Better Algorithms to Minimize the Cost of Test Paths](https://ieeexplore.ieee.org/document/6200084)

## Abstract for the paper
Model-based testing creates tests from abstract models of the software. These models are often described as graphs, and test requirements are defined as sub paths in the graphs. As a step toward creating concrete tests, complete (test) paths that include the sub paths through the graph are generated. Each test path is then transformed into a test. If we can generate fewer and shorter test paths, the cost of testing can be reduced. The minimum cost test paths problem is finding the test paths that satisfy all test requirements with the minimum cost. This paper presents new algorithms to solve the problem, and then presents data from an empirical comparison. The algorithms adapt approximation algorithms for the shortest super string problem. The comparison is with an existing tool that uses a brute force approach to extend each sub path to a complete path. One new algorithm is based on the greedy set-covering algorithm and the other is based on finding a matching over a prefix graph. The comparison was performed on open software and showed that both new solutions generate fewer test paths than the brute force approach. The prefix-graph based solution takes much less time than the other two solutions when the number of test requirements is large.



## Where I found it interesting

I tried the website of Graph Coverage Web Application, and it is appearently that different algorithm execute in different speed. If we are software tester, a faster testing speed could greatly improve the efficiency of software development.

## Fork Collaboration
Hello! This is Vivian forking the repo!
=======