# The Birthday Paradox in the NBA

Have you heard of the Birthday Paradox? Discover the answer to an intriguing question: How many people need to be in a room to have a 50% probability that at least two people share a birthday? Apply these insights to explore shared player birthdays within NBA teams.

The Birthday Paradox answers the question: how many people do you need in the same room in order to have a probability of at least 50% that two people share a birthday. The answer is astonishing! You'll use your findings to find which teams in the NBA share player's birthdays.

Wikipedia article on Birthday Paradox: https://en.wikipedia.org/wiki/Birthday_problem

The focus of this quick project is to put your Data Analysis with Pandas Skills to a test.

We're going to be analyzing the "Birthday Paradox" using data from the NBA.

In particular, the Birthday Paradox refers to the counterintuitive fact that only 23 people are needed for the probability of two people having a birthday on the same day, exceeds 50%.

This project will deal, not only with Pandas skills, but also with Probability concepts and combinatorics.

The first step will be to calculate the probability of two people sharing a birthday, in a group of n people. We can use the following approximation formula:

P(n) = 1 - ((364/365) ** nC2) where nCr is Combinations of C(n, r)

nCr = factorial(n) / (factorial(r) * factorial(n - r))

Project Link: https://www.datawars.io/data-science-project/865c74c4-the-birthday-paradox-in-the-nba

Completed Project: https://beta.datawars.io/project/865c74c4-fd9e-4694-a4a0-b7cdfbd4ea71?page=1