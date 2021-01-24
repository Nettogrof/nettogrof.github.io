---
layout: page
title: Journey Step 3 - Improving your Snake
permalink: /step3/
---

## Improving your snake

To improve your snake, first you need to know why it lost some games. Looking at several games, you will probably see a pattern how your snake lost. Second, you need to find a way to prevent this kind of lost, it could be as simple as avoid being near wall, or stay away from bigger snake, etc.

To test your snake in a particular situation, you can use the [Board Generator](https://Nettogrof.github.io/battle-snake-board-generator/). The board generator, let you create manually a position that you can "send it" to your snake and see its response.

Example, my snake "Nessegrev" will go in a dead-end, if there a food in it. I could program a function to avoid dead-end, then re-create a dead-end situation with the board generator, and check if my new function works correctly or not, without having to play/check several game.

Once done, you can repeat this step several times to improve your snake each time with different mistakes your snake made.
