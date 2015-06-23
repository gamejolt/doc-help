# Scores

Scoreboards are a great way to get gamers to engage with your game through competition. The Game Jolt Game API allows you to add multiple, customized scoreboards to your game. 

## Multiple scoreboards

Create multiple scoreboards and have, for example, one for each level of the game, as well as one for global scores. Or make scoreboards that rank players by something other than points, such as time, kills, or cookies eaten.

## Guest scoring

Enable guest scoring so players without Game Jolt accounts can submit their scores. Be aware that allowing guest scoring could result in unwanted and offensive names on your scoreboard. Submitted names are case sensitive.

## Unique scores

If you enable unique scores and someone submits multiple scores, only their best will be displayed. Turn off unique scoring to make a traditional, arcade-style scoreboard where the same person can occupy multiple slots.

## Sort direction

You can set a scoreboard's sort direction to be descending (bigger numbers on top) or ascending (smaller numbers on top). Most scoreboards are descending, but you'd want to use ascending if you have a game where, for example, lower times are better, or a golf game.

## Score strings vs sort values

When logging a player's score in your game, you can make the score string different from the sort value. The **sort value** is an integer and the basis for a score's ranking. The **score string** can be more than just a number and is what shows up on the scoreboard.

Example Sort Value: `5`

Example Formatted String: `5 bubbles popped`

## Extra data

You can use the extra data field to collect additional information such as play time, number of keystrokes, etc. to weed out cheaters. The user will never see this--it is accessible only from the developer dashboard.
