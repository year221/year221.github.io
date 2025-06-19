---
layout: default
title: year221 - Personal Website
description: Welcome to year221's personal space on the web
---

# year221

Welcome to my personal space on the web

## About Me

Hello! I love learning about new things and building new things with them. 

## Hobby Projects

### Card Game Table
I created this game during the first year of the COVID Pandemic, so that I would be able to play card games with my friends online when all of us were staying at home all the time. I was not able to find an existing online game application whose rule matches the game rule that we were playing with. 

Typical online card game is designed for straingers playing together, and as a result, the application has two important functionalities:
1. Keep the game's data in sync among all the clients the players are interacting with. 
2. Enforce the rule of the game, including declare winners. 

I realized that for a online card game for friends to play the game together, functionality 2 is not required. Therefore, all I need to build are:  
1. Simulate a game table
2. A card can be moved from one position of the table to another position
3. For each card, a subset of players see its front and rest of the players would see its back. 

I initiallly made this game in Python https://github.com/year221/cardgameFYF using arcade and zmq. The whole game is configured by a yaml file which defines the possible positions for cards in the table and constraints on each position. 
```
https://github.com/year221/cardgameFYF/blob/master/games/zhaopengyou.yaml
```
A different yaml file could define a different game table. 
 

It is not easy to get some of my friends to install Python clients so I converted this game into Javascript while learning how to program in this language. https://github.com/year221/cardgametable The game is built on top of [Phaser](https://phaser.io/) and socket. 


### Membership Card
I made this program for a community center that I volunteered for. We have a need to print membership card and the membership information is hosted in www.wildapricot.com. 
https://github.com/year221/cccmembercard

## Get In Touch

I'm always interested in connecting with fellow developers and creators.

- [GitHub](https://github.com/year221)

*Last updated: 2025*