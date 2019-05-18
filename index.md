## Bayesian Hope For Your Summer Ambitions

---

### The Math Works Out

Whether you’re a grizzled PhD student or green undergrad, you’ll be asked around May an innocent question, ripe with feeling and heavy with gravitas.

"What are you doing this summer?"

For as long as any millenial can remember, generation after generation of hungry, bright-eyed students have dedicated precious summer months to one thing and one thing only - interning. 

And as visions of an idyllic corporate dream fade, the post-offer euphoria is jettisoned by the harsh uncertainty: a full-time offer is far from guaranteed. 

Take my friend, a summer intern at a large US-based technology firm (ie. FAANG).

He feels blissfully thrilled for a moment before the brooding shadows of his brain begin contemplating the odds of a fulltime offer.

And as fantasy and doubt intermingle throughout his psyche, he is left wondering: 

"What is the probability that I'll be hired on fulltime as a summer intern?"

Well, good thing we can use statistics to soothe us with the math of dealing with uncertainty. 

### Thanks Bayes

<img src="images/EQ_4.JPG?raw=true"/>

Bayes Rule, pictured above, will tell us the probability of an event based on an estimate of the prior distribution and corresponding likelihood.

The resulting probability is known as the posterior distribution with its initial input, the prior distribution, functioning as a proxy measurement of previous knowledge or information associated with the event. 

The posterior probability of a population parameter theta (θ) given an observed dataset is:

<img src="images/EQ_2.JPG?raw=true"/>

where

<img src="images/EQ_1.JPG?raw=true"/>

A parameter is a summary metric for a population, which we can informally define as the entire set of observations that constitute the group of interest we're measuring for; this is distinct from the terms sample and statistic which are the corresponding analogs for some portion of the population less than the whole.

With that understanding, the likelihood is the density function of seeing the observed dataset conditioned on the summary metric being exactly Θ. This is called the likelihood, defined as:

<img src="images/EQ_3.JPG?raw=true"/>

The likelihood is multiplied by the prior class probability which is a measure of what the probability was of observing the outcome prior to observing the data:

<ig src="images/EQ_6.JPG?raw=true"/>

We don't have to think too hard to see that the prior and posterior distributions are reversed in terms of sequencing of predictor versus outcome or probability of Θ given observation data versus P of observing data given Θ:

EQ_12

For those who are rusty on their stats terminology, the density function is simply a bar graph of the relative frequency of observing some categorical or continuous variable within the entire populations. 

For the case of the continuous variable, the x-axis units interval denoted in infinitely small intervals with infinitely large sample size which converges then to that density function. 

Returning to our procedure, we take the likelihood and multiply it by the prior probability of observing theta (Θ). The prior is what you believed before you saw the evidence and the likelihood of seeing that evidence if your hypothesis is correct.

In the demoniator, we divide by the normalizing constant known as P(Data) to adjust the product of the prior and likelihood by the probability that the . At the risk of redundancy, the full equation is show below as a reminder:

<img src="images/EQ_4.JPG?raw=true"/>

This sum to one of must be the case because by definition the density function shows the probabilities of each possible value that the the random variables occupy an outcome summing to one. 

In math jargon we say that the density functions represent a complementary dijoint set plotted as a function of inverse probability.

In MBA jargon, we might call it a MECE (mutually exclusive collectively exhaustive) list reweighted to account for probabilistic ideas.  
In the denominator we have the normalizing constant which can be thought of as the portion of all possibilities and their cumlative probabilities. 

We divide by this figure in order to mathematically produce a proportion between zero and one, representing the likelihood of that evidence under any circumstances. 

In a sometimes problematic calculation, we may have to perform a high dimensional inegrations across the full set of disjoint complementary predictor values proves to be no trivial task:

<img src="images/EQ_5.JPG?raw=true"/>

Practioners may opt to use numerical estimation methods such as MCMC (Markov Chain Monte Carlo) to deal with these thorny computations.

### So what about our friend?

So in the case of my intern friend, what is the appropriate prior distribution to use? 

Well, we can think of the outcome of my friend getting an offer or not as a random variable.

A random variable is essentially the outcome of an result generation process like a coin flip or roll of a die.

Random variables generated out of this kind of process are known as a Bernoulli trial, which is a special case of the binomial theorem setting n, or the number of trials to one to correspond to the reality that there'll be only one result - either he gets the fulltime offer or he doesnt.

EQ_8

For both the Bernoulli trial and bionmial theorem, the beta distribution is the corresponding conjugate prior.

The beta distribution is a family of continuous probability distributions defined on the interval from zero to one parametrized by two positive shape parameters, denoted by α and β, that appear as exponents of the random variable and control the shape of the distribution:



EQ_7

If we set alpha and beta to be one, we get a probability of 0.5 we gte the following result:

EQ_9

But if we assume the mean of the probability was left of cetner such as, the probability would be greater than one.

We might correspond this to information from sound bites heard by ________, which can form the basis of a prior.

Or the observation that ____ in his life typically succeeded.

Which is all to say if we did the decision tree something like this:

EQ_10

And did all the math out to be something like this:

EQ11

Here are the results you'd get with the __ in the ___ row and ___ in the other row.

<img src="images/Sensitivity_table.JPG?raw=true"/>

### So what does this all mean?

He should feel good and optimisti cabout the future while acknowledging there is some level of uncertainty simply outside of his control. And

 it's funny because if you subscribe at all to the power of positive thinking or habiets of mind, then this is how he should have acted and believed all along. 

We didn't need all this math and statistics to get here but it sure feels nice.

## Are we being naive?

Naive bayes. Diagonal covariance matrix, every predictor random variable is independent of the others. This is likely inappropriate due to that simplifying assumption but drastically reduced the number of parameters, computational volume, and complexity cost of the learner.

<img src="images/Covariance_matrix.JPG?raw=true"/>

### We need to test our assumptions and underlying foundation

Our model is only as good as our thought quality, fit of algorithm, and data quality. 

### In conclusion, being positive never hurts, mathematically speaking.

## Archive

---

[Shower Thoughts (May 2019)](/sample_page)
