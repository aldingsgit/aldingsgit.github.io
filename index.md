## Bayesian Hope For Your Summer Ambitions

---

### The Math Works Out

Whether you’re a grizzled PhD student or green undergrad, you’ll be asked around May an innocent question, ripe with feeling and heavy with gravitas.

What are you doing this summer?

For as long as any millenial can remember, generation after generation of hungry, bright-eyed students have dedicated precious summer months to one thing and one thing only-interning. 

And as visions of an idyllic corporate dream fade, the post-offer euphoria is jettisoned by the harsh uncertainty: a full-time offer is far from guaranteed. 

Take my friend a summer intern at a well-known tech firm (ie. FAANG).

He feels blissfully thrilled for a moment before the brooding shadows of his brain begin contemplating the odds of a fulltime offer.

And as fantasy and doubt intermingle throughout his psyche, he is left wondering: 

"What is the probability that I'll be hired on fulltime as a summer intern?"

Well, good thing we can use statistics to soothe us with the math of dealing with uncertainty. 

### Thanks Bayes

Bayes Rule will tell us the probability of an event based on an estimate of the prior distribution.

The resulting probability is known as the posterior distribution with its initial input, the prior distribution, functioning as a proxy measurement of previous knowledge or information associated with the event. 

More formally, the prior distribution is the probability of a population parameter theta (θ) given an observed dataset.

A parameter is a summary metric for a population, which we can informally define as the entire set of observations that constitute the group of interest we're measuring for; this is distinct from the terms sample and statistic which are the corresponding analogs for some portion of the population less than the whole.

With that understanding, the prior distribution is the density function of seeing the observed dataset conditioned on the  summary metric being exactly Θ, or the likelihood, which in math notation is  P(Data | Θ).

For those who are rusty on their stats terminology, the density function is simply a bar graph of the relative frequency of observing some categorical or continuous variable within the entire populations. 

For the case of the continuous variable, the x-axis units interval denoted in infinitely small intervals with infinitely large sample size which converges then to that density function. 

Returning to our procedure, we take the likelihood and we multiply it by the prior probability of observing theta (Θ) before dividing by the normalizing constant known as P(Data) to adjust the density function to sum to one. 

This must be the case because by definition the density function shows the probabilities of each possible value that the the random variables occupy an outcome summing to one. 

In math jargon we say that the density functions represent a complementary dijoint set plotted as a function of inverse probability.

In MBA jargon, we might call it a MECE (mutually exclusive collectively exhaustive) list reweighted to account for probabilistic ideas.  
In the denominator we have the normalizing constant which can be thought of as the portion of all possibilities and their cumlative probabilities. 

We divide by this figure in order to mathematically bound between zero and one the proportion of all possibile outcomes and their cumulative probability to the set of all possible outcomes. 

In a sometimes problematic calculation, we may have to perform a high dimensional inegrations across the full set of disjoint complementary predictor values proves to be no trivial task:

EQUATION

At times,  

If we think carefully about this, this is the exact reversal of logical induction that we are trying to estimate; we'd like to know the probability of observing our desired parameter theta given that we are observing the observed dataset (which we are): P(Θ | Data)


in other words, we see he posterior distribution: the probability of a population parameter given the data set.

This idea was immortalized either elegantly or tersely (depending on whether you’re a math major):

P(A | B)= \frac{P(B|A)P(A)}{P(B)}

### So what about our friend?

So in the case of my intern friend, 




He should feel good and optimisti cabout the future while acknowledging there is some level of uncertainty simply outside of his control. And

 it's funny because if you subscribe at all to the power of positive thinking or habiets of mind, then this is how he should have acted and believed all along. 

We didn't need all this math and statistics to get here but it sure feels nice.

[Project 1 Title](/sample_page)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

TEXT


## Shower Thoughts (5/19)

---

### Spring

Every May, the endless epoch of New England winter exhales one final time.

Crawling out from the depths of the frozen desert, 

Summer emerges, naked and trembling,

Slowly inching along,

Before one day, growing too big, 

The pregnant bloom of the plodding equinox sweeps aside the dry tundra.

But shame on me for forgetting..

There's no such thing as a New England spring!

Next year, I won't be fooled again.


---
<!-- Remove above link if you don't want to attibute -->
