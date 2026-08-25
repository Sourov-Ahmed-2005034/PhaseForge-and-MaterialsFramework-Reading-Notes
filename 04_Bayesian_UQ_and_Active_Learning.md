# Bayesian UQ and Active Learning: Future Learning Interests

## Why This File Is Intentionally Short

Bayesian inference, uncertainty quantification, and active learning are not areas in which I currently have research experience.

They are included because they are part of the PhaseForge opportunity and because I would like to understand how they can improve computational thermodynamics.

I do not want this repository to imply that I have already implemented these methods.

## My Current Starting Point

My formal background includes a 60-hour Machine Learning with Python course and a small Random Forest regression exercise in my Al-Co project.

That experience is much more basic than Bayesian scientific modeling or active learning.

## Bayesian Inference: What I Currently Understand

At a basic level, I understand Bayesian inference as a framework for updating uncertainty about model parameters when new data are available.

The conceptual relation is:

```text
prior information
      +
observed data
      |
      v
updated parameter uncertainty
```

I have not implemented Bayesian parameter estimation in a research project.

## Uncertainty Quantification: Why It Interests Me

A computational prediction can appear precise even when:

- the available data are limited;
- model parameters are uncertain;
- the model is being used outside well-tested conditions.

I would like to learn how uncertainty can be represented and propagated into phase-stability predictions.

I have not yet performed such an analysis.

## Active Learning: What I Want to Understand

My current basic understanding is that active learning can help decide which new calculation or experiment would be most informative for improving a model.

Conceptually:

```text
current data
      |
      v
current model
      |
      v
identify an informative next point
      |
      v
new calculation or experiment
      |
      v
update the model
```

I have not implemented an active-learning loop.

## Questions I Would Like to Study in a PhD

- How can uncertainty in CALPHAD parameters be estimated?
- How does uncertainty affect predicted phase boundaries?
- How can uncertainty be used to choose new calculations?
- What makes an active-learning strategy effective for expensive materials calculations?
- How can these methods be integrated into a reproducible computational workflow?

## Current Limits

I do not currently claim experience in:

- Bayesian statistics research;
- Markov-chain Monte Carlo;
- posterior sampling;
- uncertainty propagation;
- acquisition functions;
- active-learning implementation;
- differentiable thermodynamics;
- agentic scientific systems.

These are future learning areas.

## Why This Still Fits My Research Direction

My current experience is in generating computational materials data.

A future research direction I find interesting is learning how to decide:

```text
Which data are reliable?
How uncertain are the predictions?
Which calculation should be performed next?
```

That is the level at which Bayesian UQ and active learning currently connect to my research interests.
