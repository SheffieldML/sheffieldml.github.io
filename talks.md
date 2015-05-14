---
layout: page
title: Talks
tagline: talks from ML@SITraN
---


* * * * *

### Machine learning approaches to change detection

**Song Liu** - Tokyo Tech.
 18 March 2014, at 14:00 hrs.
 SITraN, room B01.


[Click here to see the slides.](./slides/2014-03-18-song-liu.pdf)

* * * * *

### Austerity in MCMC Land: Cutting the Metropolis-Hastings Budget

**Yutian Chen** - University of Cambridge.
 6 March 2014, at 10:30 hrs.
 Barber House, room A19.

Can we make Bayesian posterior MCMC sampling more efficient when faced
with very large datasets? We argue that computing the likelihood for N
datapoints in the Metropolis-Hastings (MH) test to reach a single binary
decision is computationally inefficient. We introduce an approximate MH
rule based on a sequential hypothesis test that allows us to accept or
reject samples with high confidence using only a fraction of the data
required for the exact MH rule. While this method introduces an
asymptotic bias, we show that this bias can be controlled and is more
than offset by a decrease in variance due to our ability to draw more
samples per unit of time.


[Click here to see the slides.](./slides/2014-03-06-yutian-austerityMCMC.pdf)

* * * * *

### Maximum utility unitary coherent perception vs. the Bayesian brain

**Charles Fox** - University of Sheffield.
 7 February 2014, at 10:30 hrs.
 SITraN, room B03.

Our subjective experience of the world is 'unitary coherent' (UC).
'Unitary' means we only perceive one interpretation at a time rather
than a blur of multiple possible worlds. 'Coherent' means that we almost
always perceive scenes that do not contain contradictory parts. While
this form of first-person perceptual experience may seem obvious, it is
in opposition to the requirements of optimal decision making, and to
some forms of the 'Bayesian brain' hypothesis. We hypothesise that there
are at least three types of 'Bayesian' action selection occurring in
cognition, including a 'maximum utility (MU) percept' strategy that
makes use of UC percepts. We give evidence from a video game experiment
that is compatible with MU/UC perception and action selection, and is
incompatible with optimal actions. Furthermore, it is compatible with
the presence of utility bias in MU/UC perception: by changing the
available actions we may be able to manipulate the subject's percept of
a fixed ambiguous stimulus.


[Click here to see the article.](http://staffwww.dcs.shef.ac.uk/people/C.Fox/fox_unitary_coherent.pdf)

* * * * *

### Bayesian Machine Learning for Controlling Autonomous Systems

**Marc Deisenroth** - Imperial College London / TU Darmstadt.
 17 January 2014, at 10:30 hrs.
 Barber House, room A19.

Autonomous learning has been a promising direction in control and
robotics for more than a decade since learning models and controllers
from data allows us to reduce the amount of engineering knowledge that
is otherwise required. Due to their flexibility, autonomous
reinforcement learning (RL) approaches typically require many
interactions with the system to learn controllers. However, in real
systems, such as robots, many interactions can be impractical and time
consuming. To address this problem, current learning approaches
typically require task-specific knowledge in form of expert
demonstrations, pre-shaped policies, or specific knowledge about the
underlying dynamics.

In the first part of the talk, we follow a different approach and speed
up learning by efficiently extracting information from sparse data. In
particular, we learn a probabilistic, non-parametric Gaussian process
dynamics model. By explicitly incorporating model uncertainty into
long-term planning and controller learning our approach reduces the
effects of model errors, a key problem in model-based learning. Compared
to state-of-the art RL our model-based policy search method achieves an
unprecedented speed of learning. We demonstrate its applicability to
autonomous learning in real robot and control tasks.

In the second part of my talk, we will discuss an alternative method for
learning controllers based on Bayesian Optimization, where it is no
longer possible to learn models of the underlying dynamics. We
successfully applied Bayesian optimization to learning controller
parameters for a bipedal robot, where modeling the dynamics is very
difficult due to ground contacts. Using Bayesian optimization, we
sidestep this modeling issue and directly optimize the controller
parameters without the need of modeling the robot's dynamics. 

[Click here to see the slides.](./slides/2014-01-17-marc-deisenroth.pdf)

* * * * *

### Spatio-temporal Gaussian process modelling

**Arno Solin** - Aalto University.
 15 November 2013, at 11:00 hrs.
 SITraN, room B03.

Many physical and biological processes include both spatial and temporal
features. Spatio-temporal modeling under the machine learning paradigm
of Gaussian process (GP) regression has demonstrated prominent results.
However, the appealing Bayesian treatment by GP regression is often
difficult in practical problems due to computational complexity.

This presentation focuses on presenting various spatio-temporal Gaussian
process regression problems as infinite-dimensional state space models.
The advantage of this formulation is that it allows the use of
computationally efficient linear-time-complexity infinite-dimensional
Kalman filtering and smoothing methods. The approach in this
presentation is primarily application-driven. The feasibility of
infinite-dimensional Kalman filtering is demonstrated by modeling daily
temperature variation around the globe, noise in fMRI brain data, and
rainfall data.

Arno will also shortly present the state space methods that he has
implemented in GPy during his visit. 

[Click here to see the slides.](./slides/2013-11-19-Solin-Sheffield-1.pdf)

* * * * *

### Classical meets pop: Wiener filtering vs. Gaussian process regression

**Simo Särkkä** - Aalto University.
 15 November 2013, at 14:00 hrs.
 SITraN, room B03.

Wiener filtering and smoothing (Wiener, 1949) are concerned with
estimation of values of a Gaussian process (or field), described via a
covariance function, from noisy measurements made from it. Gaussian
process regression (Rasmussen & Williams, 2006) is concerned with
estimation of values of a Gaussian process (or field), described via a
covariance function, from noisy measurements from it. The aim of this
talk is to discuss connections (or the equivalence) between Wiener
filtering and Gaussian process regression.

* * * * *

### On the reference predictive approach for covariate selection

**Aki Vehtari** - Aalto University.
 6 November 2013, at 11:00 hrs.
 SITraN, room B51.

* * * * *

### Gaussian process survival models

**Aki Vehtari** - Aalto University.
 6 November 2013, at 16:00 hrs.
 SITraN, room B01.
 
[Click here to see the slides.](./slides/slides_varanasi_sheffield-1.pdf)

* * * * *

### Smooth metric learning - in which manifold learning is about learning manifolds

**Søren Hauberg** - Max Planck Institute for Intelligent Systems.
 In collaboration with: Oren Freifeld (MIT), Philipp Hennig (MPI-IS) and
Michael Black (MPI-IS).
 Thursday 10th of October, at 16:00 hrs.
 SITraN, room B03.

Many modern machine learning techniques rely on the specification of an
inner product (often in the form of a kernel), which allows us to
measure similarity between observations. Unsurprisingly, the choice of
inner product has great impact on the final statistical model. Picking a
suitable inner product is, however, often difficult as the parameters
that work well in one region of your input space may not work well in
other regions. We suggest to apply different inner products in different
parts of the input space under the constraint that the inner product
structure changes smoothly. With this suggestion, we move away from the
well-established Hilbert space models and into the domain of Riemannian
manifolds. We show how to learn a smoothly changing inner product from
data and how to generalise linear regression, principal component
analysis and more. The proposed algorithms require solving vast amounts
of ordinary differential equations numerically, which consitute a
computational bottle-neck. We therefore inverstigate techniques for
solving these equations using Gaussian processes, which allows for great
computational gains.

* * * * *

### Gaussian process modelling of multiple short time series

**Antti Honkela** - Aalto University.
 18 June 2013, at 16:30 hrs.
 SITraN, room B03.

* * * * *

### Bayesian network inference for large scale data

**Mattia Prosperi** - University of Manchester.
 14 May 2013, at 14:00 hrs.
 SITraN, room B03.

Identification of prognostic factors/patterns and inference of
prediction models from large data sets is a challenge, especially when
in presence of high-dimensionality, sparseness, heterogeneity, skewness
and missing values. Off-the-shelf statistical learning methods include
linear models, decision trees, tree ensemble, and Bayesian networks.
Likewise, several methods for data pre-processing and feature selection
approaches are available. Bayesian networks are becoming popular because
they describe casual dependencies via interpretable graphical outputs.
However, optimising simultaneously attribute set and network topology is
computationally expensive. In this seminar we compare different
modelling approaches within a robust validation framework.

* * * * *

