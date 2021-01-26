---
layout: page
title: Journey Step 6 - Thinking ahead
permalink: /step6/
---

## Thinking Ahead

---

To be able to move forward in ranking/division, your snake will need to be able to think several move ahead, like a chess engine will analyze both 12-20 moves ahead. 

There's several ways to do this, you will need to be able to simulate moves. That's a tricky part because you have to implement a function that generate the "next board", example if my snake head is at (X:2, Y:3) and move up  then my snake head will be at (X:3, Y:3), and my tail have also "move". Same for all snakes on board.

Example, with just two snakes on board, if both snakes have 3 possibles moves that lead to 9 "different future board" in depth 1. If still 3 possibles moves by snake, it will be 81 future boards in depth 2. That can grow very quickly, even worst with more snakes.

To find the best possibles outcome for your snake, you need some kind of "Tree search" and some evaluation function. 

### Evaluation function

---

The evaluation function can be simple as "Did the snake is alive, or what is the snake length, etc"  or it can be more complexe "Did the snake control most of the board, or did the snake control the center, etc".

A basic evaluation function, may let your snake more time to search deeper, but a more complexe/slower evaluation function may help to choose the best move quicker in the tree search.



### Tree Search

---

Tree search isn't an easy thing to do, but some tree search algorithm are easier like the "minMax". I suggest to Google "minmax algorithm" with the programming language you use. I'm sure that you'll find tutorials and examples.

There's a lot of algorithm, you can learn about it on [wikipedia](https://en.wikipedia.org/wiki/Tree_traversal)


### A lot of testing

---

Should you made an better but slower evaluation function, or should you use another tree search ?  To answer that, you will need a lot of testing, don't forget Performance testing from Step 4.
