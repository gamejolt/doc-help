---
title: Jam Voting Results
---

# How are jam voting results calculated?

We use a system of weighted averages, in which higher occurrences of the same score are given more value, or "weight". Weighted averages prevent a game with a single 5 rating from trumping games with, for example, several 4 ratings. Similarly, the ranking of a game with several high ratings won't get destroyed by a single low rating.

# How does the weighted averaging work?

The base system used for weighting is a simplified Bayesian method. Bayesian probability can be defined thusly:

_Bayesian probability belongs to the category of evidential probabilities; to evaluate the probability of a hypothesis, the Bayesian probability specifies some prior probability, which is then updated in the light of new, relevant data (evidence)._

This matches very closely with what we desire in a voting system. Namely, that we have a small set of data, but would like to make an informed decision about the probability that a game should be given a certain rating. Think about the case of a straight average, where a game with one 5 rating would get an average of 5. A game with three 5's and one 4 would get an average of 4.75. That would rank it below the game with just one vote.

The reason is that we don’t have enough data to assume the game with an average of 5 really does deserve a 5. It might, but we only have one vote, so it’s unlikely. The probability is currently low. As the game amasses more votes, though, the probability that the game deserves the average that it’s been given increases.

So, we start off every game at the average. Then as the game gets more votes, the probability increases towards the unweighted average, and the weighted average is pulled either up or down.
