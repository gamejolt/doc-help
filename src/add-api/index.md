# How do I add scoreboards and trophies to my game?

First, you need to implement the Game API in your game's code. Then, you can add scoreboards and trophies to your game.

## Scoreboards

You can add multiple scoreboards to a game, so you could have, for example, one for each level of the game, as well as a global scoreboard. Or, you could make one that ranks players by something besides points, like total time or number of jumps. You have control over sorting options, so you could make a traditional scoreboard, where the same person can occupy multiple slots, or you could make it so that only someone's best score is displayed. You can enable guest scoring, so players don't need an account to submit a score. You can even attach extra, hidden data to scores (for verification, tracking, or other uses).

## Trophies

Trophies come in bronze, silver, gold, and platinum; the material corresponds to how easy or difficult they are to earn. You can give your trophies custom art and clever titles. You can make secret trophies that aren't completely revealed until they are won. You can keep trophies hidden to test them out.

### What are the requirements and guidelines for trophy images?

WAITING ON INFO

## Implementing the API

Implementing the Game API allows you to not only make scoreboards and trophies, but also store data online, log game sessions, and more. Everything you could possibly need to know about it is in the [Game API documentation](https://github.com/gamejolt/doc-game-api).

You don't have to start from scratch with the API. See if there's a community-written library or plugin available for the engine/language/creation tool you use [here](/game-api/index.md).

## Adding scoreboards and trophies

After you have implemented the Game API in your game, you can create and manage scoreboards and trophies. Go to your [developer dashboard](http://gamejolt.com/dashboard/) and select the game from under "Your Games". You will be taken to the game's overview page. Visit the "Game API" tab, where you will be able to choose from "Trophies", "Scores", "Data Storage", and "API Settings".

[What is the Game API?](/game-api/index.md)

[How do I use data storage in my game?](/add-storage/index.md)

[Where is the private key for my game?](/private-key/index.md)
