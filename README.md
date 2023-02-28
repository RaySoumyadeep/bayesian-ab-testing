# A/B Testing to Distinguish Impact of Version of Landing Page on purchase conversion.

![ab-test.webp](https://github.com/RaySoumyadeep/bayesian-ab-testing/blob/main/assets/ab-test.webp)

Established companies like Booking.com report constantly run thousands of AB tests at the same time. And newer growing companies like Duolingo attribute a large chunk of their success to their culture of experimentation at scale.

With so many experiments, one question comes natural: in one specific experiment, can you leverage information from previous tests? How? In this project, we will try to answer these questions by introducing the Bayesian approach to AB testing. The Bayesian framework is well suited for this type of task because it naturally allows for the updating of existing knowledge (the prior) using new data. However, the method is particularly sensitive to functional form assumptions and apparently innocuous model choices can translate in sensible differences in the estimates, especially when the data is very skewed.

In online randomized controlled experiments, specifically A/B testing, you can use the Bayesian approach in 4 steps:

1. Identify your prior distribution.
2. Choose a statistical model that reflects your beliefs.
3. Run the experiment.
4. After observation, update your beliefs and calculate a posterior distribution.
