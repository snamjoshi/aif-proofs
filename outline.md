# Outline for "The Equations of Active Inference"

About this book

**Chapters**

1. Fundamentals
   1. Generative models
   2. Bayes' theorem
   3. Hidden state estimation (MAP and MLE)
2. Variational Bayesian inference
   1. Variational free energy
   2. G-form of variational free energy
   3. D-form of variational free energy
   4. C-form of variational free energy
   5. E-form of variational free energy
   6. MAP and MLE forms of variational free energy
   7. The mean-field approximation
   8. Time-dependent variational free energy
   9. The Bethe approximation
   10. Fundamental theorem of mean-field variational inference
3. Predictive coding
   1. The generative model for predictive coding
   2. Variational free energy under Dirac $\delta$ assumptions
   3. Update equation for variational density mean (perception)
   4. Update equation for prior mean (perception)
   5. Update equation for prior variance (attention)
   6. Update equation for likelihood variance (attention)
   7. Update equation for parameters (learning)
   8. Variational free energy update rules
   9. Hierarchical predictive coding
4. Continuous state-space active inference
   1. The basic generative model for continuous state-space active inference
   2. Variational free energy under the Laplace/Quadratic approximation (univariate)
   3. Variational free energy under the Laplace/Quadratic approximation (multivariate)
   4. Variational free energy under the Laplace/Quadratic approximation and diagonal covariance matrices
   5. The generalized state-space model (including generalized prediction errors)
   6. Variational free energy for the generalized state-space model and diagonal covariance matrices
   7. Variational free energy for the generalized state-space model using the generalized precision matrix
   8. Gradient flow of hidden states (univariate and multivariate cases, generalized case)
      1. Univariate
      2. Multivariate
      3. Generalized
   9. Gradient flow of autonomous states (univariate and multivariate cases, generalized case)
      1. Univariate
      2. Multivariate
      3. Generalized
   10. Gradient flow of action (univariate and multivariate)
   11. The complete generalized state-space model (with first and second-order parameters)
   12. Variational free energy for the complete generalized state-space model
   13. Gradient flows for first and second-order parameters
   14. Solving the initial value problem (Euler, Ozaki, etc.)
   15. State-dependent precision
   16. Hierarchical models
5. Expected free energy and discrete variational free energy
   1. Policy-dependent variational free energy
   2. Policy-independent variational free energy
   3. Prior preferences and biased generative models
   4. B-form of expected free energy
   5. EP-form of expected free energy
   6. GE-form of expected free energy
   7. GC-form of expected free energy
   8. GD-form of expected free energy
   9. I-form of expected free energy
   10. RO-form of expected free energy
   11. RS-form of expected free energy
   12. Matrix forms of variational free energy
       1. Policy-dependent
       2. Policy-independent
   13. Matrix forms of expected free energy
   14. Origins of expected free energy
6. Discrete state-space active inference
   1. The basic generative model for discrete state-space active inference
   2. Matrix form of exact hidden inference (static)
   3. Matrix form of exact hidden inference (dynamic)
   4. Forward and backward smoothing
   5. Action selection
   6. Path-based policy computation
   7. Policy-independent state inference
   8. Policy-dependent state inference
   9. Gradient flow based VFE minimization
   10. Generative model for discrete state-space active inference for learning
   11. Dirichlet updates (a, b, c, d, e)
   12. Dirichlet updates (log form)
   13. Learning and forgetting rates
   14. Parameter information-seeking term
   15. Habit learning
   16. The variational policy density
       1. Variational free energy dependence
       2. Habit-dependence
   17. Generative model for discrete state-space active inference for attention
   18. Precision/attention updates
   19. Novelty seeking
   20. Factorial models
   21. Hierarchical models
   22. Hierarchical and factorial models
   23. State-based prior preferences
7. Variations on free energies
   1. Generalized free energy
   2. Free energy of the future
   3. Predicted free energy
   4. Free energy of the expected future
   5. Bethe free energy
   6. Constrained Bethe free energy
8. Extensions
   1. Action-perception divergence
   2. Renyi bound
   3. Sophisticated inference
   4. Federated belief sharing
   5. Inductive planning
   6. Renormalizing generative models
   7. Hybrid generative models
9. Factor graphs and message passing
   1. Belief propagation
   2. Message passing for the hidden Markov model
   3. Variational message passing
   4. Message passing for generalized filtering
   5. Message passing for partially observable Markov decision processes
   6. Node rules
10. The free energy principle
    1. The ergodic density
    2. External and sensory state entropy
    3. Sensory state entropy bound
11. Extras
    1. Generalized coordinates of higher-order motion (with and without autonomous states)
    2. Generalized measurements
    3. Sampling continuous sensory data
    4. Bayesian model reduction (structure learning)
    5. Bayesian model expansion (structure learning)

**Appendices**

1. Discrete state-space notation
2. Continuous state-space notation



**Extras**

1. Parameter estimation (univariate)
2. Parameter estimation (multivariate)
3. Linear Gaussian systems
4. Factor analysis and EM
5. Variational inference vs. EM



**Notes**:

* I need to also mention the cases where the autonomous state connects to the observation model. There are special equations for this particular case.