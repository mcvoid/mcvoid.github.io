---
title: Dungeons
weight: 1
---
# Dungeons

Steps to dungeon generation:

1. Roll 2d6. This is your number of rooms, typically around 7 total. Increase or decrease the number or dize of the dice for larger or smaller dungeons.
2. Draw a graph of "nodes", arranging them in a grid. 1 node for each room.
3. Pick a node with no connections to other nodes, at random.
4. If the node is on the edge of the graph, roll 1d4.
    1. On a roll of 1-3, draw that many lines connecting that node to its neighbors. 
    2. On a roll of 4, this is a secret room. Draw 1 line to a neighbor marked with an "S".
5. If the node is not on the edge of the graph, roll 1d6.
    1. On a roll of 1-4, draw that many lines connecting that node to its neighbors. 
    2. On a roll of 5, this is a secret room. Draw 1 line to a neighbor marked with an "S".
    3. On a roll of 6, this is a secret passage. Draw 2 lines to neighbors marked with an "S".
6. If there are still nodes with no connections to other nodes, go to Step 3.
7. Jaquaying the dungeon:
    1. Manually tweak the connections so there are at least two loops.
    2. Designate 2-3 nodes as having entrances: give them a line to outside the grid. Nodes not on the edge should have the entrances be directly above or below.
    
