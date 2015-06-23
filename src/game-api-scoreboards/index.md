# Scores

Scoreboards are a great way to get gamers to engage with your game through competition. The Game Jolt Game API allows you to add multiple, customized scoreboards. 

## Multiple Scoreboards

Add multiple scoreboards so you could have, for example, one for each level of the game, as well as a global scoreboard. Or, you could make one that ranks players by something besides points, like total time or number of jumps.

## Guest Scoring

Enable guest scoring for players without Game Jolt accounts can submit their score. Allowing guest scoring could result in unwanted and offensive names on your scoreboard. Submitted names are case sensitive.

## Unique Scoring

You have control over sorting options, so you could make a traditional scoreboard, where the same person can occupy multiple slots, or you could make it so that only someone's best score is displayed.

## Score Strings vs Sort Values

When logging the user's score in your game, you can pass in a different value for the score's string/text value, and a different value for the sort. The reason for this is for when you want to format your score differently than just a numeric value.

Example Formatted String: `5 bubbles popped`

Example Sort Value: `5`

The formatted string is what will show up on your game's page. The sort value is the numeric value that Game Jolt uses to rank the score among the other scores on the scoreboard.

## Extra data

Use the extra data field to collect additional information such as playtime, number of keypress, etc. to weed out cheaters. The user will never see this, it is only accessible from the developer’s dashboard.
