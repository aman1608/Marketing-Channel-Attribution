# Marketing-Channel-Attribution
## About:
Markov Chains are named after Russian mathematician Andrei Markov and provide a way of dealing with a sequence of events based on the probabilities dictating the motion of a population among various states. Consider a situation where a population can exist in two or more states. A Markov Chain is a series of discrete time intervals over which a population distribution at a given time (t = n; n = 0,1,2,….,k) can be calculated based on the distribution at an earlier time (t = n – 1) and the probabilities governing the population changes. Most specifically, a future distribution depends only on the most recent previous distribution. In any Markov process there are two necessary conditions:
•	The total population remains fixed.
•	The population of a given state can never become negative.
If it is known how a population will redistribute itself after a given time interval, the initial and final populations can be related using the tools of linear algebra. A matrix T, called a transition matrix, describes the probabilistic motion of a population between various states. The individual elements of the matrix reflect the probability that a population moves to a certain state. The two conditions stated above require that in the transition matrix each column sums to 1 (i.e. the total population remains unchanged) and there are no negative entries.

## Applications:
Markov chains can be used to model situations in many fields, including biology, chemistry, economics, and physics. It is also widely used in Marketing; say, to understand the effectiveness of channels for promotion. We have used a dataset based on this context. Let us find how Markov chains can help us to prioritize the budget spending for the channels of promotion.
