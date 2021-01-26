---
layout: page
title: Journey Step 4 - Time to get serious
permalink: /step4/
---


## Time to get serious

Now that you have a decent snake, it's time to get serious. If you don't use a source code management / version control, it's time ! I personaly use [Github](https://github.com), it's easy to use, and you can have public or private repositories.  Public mean everyone will be able to see your code,  private not.  [Github](https://github.com) is also a sponsor of [Battlesnake](https://play.battlesnake.com).  There's plenty source code management tool, I suggest to use one that you like.

### Why?

The main reason I suggest to use a source code management tool, it's because we never know when we gonna make a feature/function that gonne make the snake worst. It's nice to able able to revert code to the point before. 

But how do we know if a new feature make our snake worst?  Testing, I'll call it Performance testing.


## Performance Testing

Performance testing will help you to check if your new feature make your snake better or worse. There's several ways to do it:
  1. The lazyest one:  register another snake , and wait several days to see which one have a better rating.
  1. The not-so-bad one: Use the [Battlesnake-CLI](https://github.com/BattlesnakeOfficial/rules/tree/main/cli) to play several game between your "old" snake vs the "new" one.
  1. The good one: Use the [Battlesnake-CLI](https://github.com/BattlesnakeOfficial/rules/tree/main/cli) to compare your both snakes against other snakes like ["Nessegrev" ones](https://github.com/Nettogrof/battlesnake-nessegrev)
  1. The Best one: Same as the good one, but run hundreds games to have a real idea. (I'll develop a tool to automate that. you can follow the developpement [here](https://github.com/Nettogrof/BattleSnake-PerformanceTesting))

