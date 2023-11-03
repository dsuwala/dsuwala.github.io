---
title: "Finding checkerboard cellular automatons"
date: 2023-11-01
draft: false
project_tags: ["python", "programming"]
status: "evergreen"
summary: "A search of cellular automatons through genetic algorithm to always get checkerboard."
links:
    another_link:
        text: "Check the code"
        icon: "fab alt brands fa-github"
        href: "https://github.com/dsuwala/small_projects/blob/main/genetic_algorithm.ipynb"
        weight: 1
---
## Summary
A cellular automaton (CA) is a grid of cells which can be in one of (finite) states line zero or 
one and a set of rules which changes states according to states of neighboring cells. One 
example of cellular automaton is [Conway's Game of Life](https://playgameoflife.com/).
This project implements a search of such cellular automaton which will evolve any starting pattern into
checkerboard. 
The search is done through genetic algorithm which in general consists of making "population" of cellular
automatons and changing that population to pass external score. The highest scoring automatons are the
result of such training.
Here is an example of such trained automaton: 

{{ $image := .Resources.Get "cellular_automaton.gif" }}
{{ $image := $image.Resize "400x" }}
<!-- ![example_gif](cellular_automaton.gif) -->
