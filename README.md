### Mathematical Recommendation Systems
In this project, we explore two algorithmic techniques for building a recommendation system:
- Non-personalised Bayesian Ranking: this algorithm produces a ranking based on the posterior distribution of the mean of a certain parameter. In the case of a recommendation system, this parameter can be the Click-Through Rate (CTR).
  Ranking is performed by random sampling from the distribution, which is updated with each new interaction, in order to compensate for the Explore-Exploit dilemma.
  The `BayesianRanking` file takes care of just this, producing a dynamic visualisation of the Posterior distributions to highlight the fit of the distribution, which becomes more and more precise and makes it possible to identify the object of greatest interest.
- Personalised Pearson Rating Prediction: in the `PearsonRatingPrediction` file, we introduce the concept of *Collaborative Filtering* through this prediction algorithm based on Pearson correlation coefficients. Although it is not a proper Machine Learning algorithm, its performance proves to be very good,
  at the expense of significant computational complexity.
