# Phase Stability and Structure Sampling: Concepts I Want to Develop

## Why This Topic Is Here

My Al-Co mini-project made me realize that calculating energies for a few random structures is not the same as determining phase stability.

This file records the basic ideas I have started to understand and the areas I would like to learn more rigorously during a PhD.

## What I Have Actually Done

For the Al-Co learning project, I generated:

```text
7 compositions
x
3 random arrangements per composition
=
21 FCC-based configurations
```

I used pretrained CHGNet to calculate static energies and then formed a constrained energy difference using selected elemental references.

This was a workflow demonstration only.

## Basic Ideas I Am Learning

### Formation-energy comparison

A structure can be compared with selected elemental reference energies using a relation such as:

```text
Delta E =
E_alloy - sum_i x_i E_i
```

The meaning depends on the chosen structures and reference states.

My current project uses a simplified constrained setup.

### Competing structures

A low energy for one configuration is not enough to prove that it is a stable phase.

Other structures and possible decomposition products must also be considered.

This is one of the key limitations of my small Al-Co project.

### Structure relaxation

My Step-78 project used unrelaxed structures.

I understand that a more rigorous energetic comparison should use a consistent relaxation procedure before comparing candidate structures.

I have not included that extension in the public mini-project because I want the repository to represent only the workflow I completed and can explain confidently.

### Random configurations versus SQS

My project uses simple random atomic arrangements.

I have learned that a more systematic representation of a chemically disordered alloy can use a special quasirandom structure, or SQS.

I have not generated SQS structures yet.

### Convex-hull idea

I am aware that a 0 K convex hull can be used to compare formation energies across composition and identify the lowest-energy combinations within a candidate dataset.

I have not performed a rigorous convex-hull study and do not present my Al-Co project as one.

## What I Want to Learn

During graduate research, I would like to learn:

- how candidate structures are selected systematically;
- how SQS structures are generated and evaluated;
- how ordered and disordered structures are compared;
- how relaxation is performed consistently;
- how reference energies are chosen;
- how a reliable convex hull is constructed;
- how finite-temperature contributions change the 0 K picture;
- how atomistic phase-stability data can connect with CALPHAD.

## Current Limits

I do not currently claim practical experience with:

- SQS generation;
- ATAT workflows;
- cluster expansion;
- systematic structure enumeration;
- rigorous convex-hull construction;
- first-principles phase-stability calculations.

These are areas I would like to learn.

## Connection to My Research Potential

My current atomistic experience gives me a practical starting point for working with structures and energies.

The next research step I want to learn is how to move from:

```text
a few selected structures
```

to:

```text
representative structure sampling
+
reliable energetic comparison
+
thermodynamic interpretation
```

That transition is directly relevant to my interest in phase stability.
