---
layout: page
title: Journey Step 5 - Automatic Unit Testing
permalink: /step5/
---

## Automatic Unit Testing

Adding more and more features/functions to your snake may cause some issue, missing let say a dead-end because to much focusing on running away from a bigger snake. 

Doing Unit testing often will help you to avoid your snake's simple mistakes. At first I used a [BattlesnakeTester](https://github.com/Nettogrof/BattlesnakeTester), that is a fork from a tool made by other developer. I adapted it to API v1, but in my todo list I plan to redo a new BattlesnakeTester because in the current it's so hard to add more tests.

I'll use the same "standard" as [Brad-coding-badly](https://github.com/BattlesnakeOfficial/coding-badly/tree/main/src/tests), because it'll be way more easier to add more tests.

I know that several (most ?) of top tier snake developer use some kind of Unit testing, because we don't want to deploy a new snake, that do stupid mistake once live in global arena or worst in tournament.

You could use a language-specific testing function, use an already made tester, or build your own automatic unit tester. It'll help you a lot in the long run.