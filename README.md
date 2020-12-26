# Web Graph Generator Version-2

This program will generate a random graph in textual form that can be visualized in WebGraphViz software.

## Concept Focus
```bash
- This program focuses on structures and also uses I/O files.
```
## Installation/Prerequisite

```bash
1. The generated graph can be visualized in WebGraphViz software (http://www.webgraphviz.com/)
2. You will need to include the vector library in the program.
3. You will need header file for random number generation and coin_flip and some other functions.
```

## Program Description

```bash
A graph is a combination of nodes and edges that connect them. Your graph should start with one of the following shapes:
	- A single node (dot) with 20% chance
	- A couple of nodes (two dots connected) with 20% chance
	- A Triangle (three dots connected) with 20% chance
	- A Square (four dots connected) with 20% chance
	- A Pentagon (five dots connected) with 20% chance
Each node should have a label that represents the order in which it spawned and a 50% chance to produce a branch, which is an edge with one of these structures attached. 
That means
	– if a branch is happening one of the shapes must be picked (and each of them has 1/5 or 20% chance to occur) and attached to the node that produced it. 
	  Older nodes should be tried for branching first. 
	  Make sure to limit your graph to a maximum of n branches happening (for easier visualization)
```
