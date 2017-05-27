---
layout: post
permalink: "projects/tic-tac-toe"
title: "Tic Tac Toe"
description: "Multi Mode Tic Tac Toe Online Game"
categories: [JavaScript]
date: 2017-05-28 01:10:00 +0530
tags: []
---

**Tic Tac Toe** is multi mode online game. The player have to update the getRow() and getC0l() functions to return the cordinates (starting from 0,0) of the cell where they want to take their turn.

There are three modes:

- **Multiplayer**: It is two player mode.
- **Random**: It is Player VS Computer mode in which Computer takes it turn, filling up random vacant cells.
- **Challenge**: It is Player VS Computer mode too but it is an unbeatable version. Player can tie the game or losse but he can never win against the computer, in this mode.

In Random and Challenge mode there are options to go First and Second too.

### Challenge Mode
The unbeatable algo is based on the same way anyone tries to play game naturally. 

- We analyze if we are winning by taking any move, in any of the 3 rows or the 3 columns or the 2 diagonals. If winning, then we thake the required the move and wins the game.

- If we are not winning, that means if the first step fails in taking any move, we then analyze if the opponent is going to win in his next turn. If found, then we take the required move to block the opponent from winning the game. 

- Now, if neither the opponent nor ourselves our winning, then we take such a move that will lead us to a win in future.

### Information

**Source Code** : <https://github.com/coding-blocks/tic-tac-toe>

### Maintainers

**Arnav** <a@cb.lk>
