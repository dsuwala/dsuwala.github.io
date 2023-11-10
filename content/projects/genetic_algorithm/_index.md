---
title: "Projects: Cellular automatons training"
type: "page"
---
## Related tech stack:
- python
- object oriented programming
- numpy & vectorization 
- matploblib with animations

## Summary
A cellular automaton (CA) is a grid of cells which can be in one of (finite) states like zero or 
one and a set of rules which changes states according to states of neighboring cells. One 
example of cellular automaton is [Conway's Game of Life](https://playgameoflife.com/).
This project implements a search of such cellular automaton which will evolve any starting pattern into
checkerboard.\
The search is done through genetic algorithm which in general consists of making "population" of cellular
automatons and changing that population to pass external score. The highest scoring automatons are the
result of such training.\
Here is an example of such trained automaton: 

{{< video src="cellular_automaton.mp4" width="400" >}}



