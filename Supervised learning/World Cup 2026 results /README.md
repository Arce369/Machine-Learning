# Predicting Football World Cup Results with Dixon–Coles, MCMC, and XGBoost

This project explores a hybrid statistical and machine learning approach to predicting football match outcomes, with a focus on World Cup scenarios. The goal is to combine classical sports analytics models with modern predictive techniques to obtain robust estimates of match probabilities and expected scores.

The project has two main objectives:

1. **Exploratory implementation. (for fun)**  
   Build a complete prediction pipeline capable of estimating the probability of each possible match result and the most likely scoreline. This includes:
   - A Dixon–Coles model for structural football parameters.
   - A Bayesian MCMC version of the same model to quantify uncertainty.
   - XGBoost regressors to capture nonlinear patterns in recent team performance.

2. **World Cup simulation.**  
   Use the predictive models to simulate entire tournament paths, including:
   - Group stage outcomes.
   - Knockout bracket progression.
   - Probabilities of reaching each round.
   - Estimated probability of becoming World Cup champion.

This framework integrates statistical modeling, Bayesian inference, and machine learning to produce a comprehensive prediction engine suitable for analysis, experimentation, and simulation.
