---
layout: post
title: You have an 89% chance of succeeding in startups
excerpt: "You have a 89% of succeeding in startups"
modified: 2015-06-22
public: false
---


I had dinner with another entrepeneur who's struggling through a pivot. He said - "I have a better chance of success in Vegas than doing a startup." This bothered me. He was joking, but it implied a bleak view of the world where the odds are stacked against you.

His view was grounded, because we often read grim statistics such as "90% of startups fail". However, a 10% chance of success is actually pretty good. It means if you try 10 times, then the chances of succeeding at least once is 65% - better odds than Vegas.

<!-- To paraphrase Churchill, "a pessimist sees the difficulty in every [statistic], but an optimist sees the opportunity in every [statistic]". -->

# Key Question

The question should not be - "what are the chances my startup will succeed?"
The question should be - "what are the chances one of my startups will succeed?"

The answer to the second question is 89%. The assumptions are:

1. Each startup has a 20% chance of success.
This is suggested by a Harvard Study[x] defining 'success' as going public, and draws data from Dow Jones’ Venture Source. It also noted the chance of success increases after each failure.

2. You will try 10 startups.
This will probably take an entire career if we assume 2-3 years per startup.

Here's a binomial distribution calculator to compute your own variables. We are interested in P(X >= 1).

[Dist Graph here]

# Optimising Success

Once the goal is to maximize the chances of succeeding at least once (P(X>=1)), then the variables to optimize become clear. In fact, financiers have used probability to manage risk for centuries.

### 1. Increase P(x)
The higher chance of success for any given trial (P(x)), the higher the chance of succeeding at least once (P(X>=1))

[Line Chart; x is P(x); y is P(X>=1)]

Many startup advice books and blogs illustrate how. For example, finding quality co-founders, having good mentors, and building a quality team.

### 2. Increase n

Trying more startups also increases P(X>=1)

[Line Chart; x is num of tries; y is P(X>=1)]

Reducing startup cycles allows for more tries. The common advice is to "fail fast". Building multiple startups in parallel will also allow more tries, but maybe reduce the chance of success in individual trials (P(x))

### 3. Reduce variance

If you have a 20% chance of creating $10m in wealth, the expected outcome is $2m. However, the variance is high. You either get $0, or $10m.

Venture capitalists reduce variance by diversifying their risk. Founders could do something similar. The logic is that one of you will make it big but you don't know who. Therefore, you could swap 1% of your equity for another founder's equity in a different company. The more companies the better, so long as you have faith in those founders. This reduces the risk for all founders and increase likelihood of a payoff for all involved. Founders having a stake in each others' companies could also improve camaraderie and collaboration.

The equity swap model could work well for accelerators.

# Conclusion

Some say the glass is 90% empty, but it will be 89% full if you pour multiple times.


