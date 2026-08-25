# Atomistic Modeling and MLIPs: My Strongest Research Bridge

## Why This Topic Is Here

Atomistic simulation is the part of the PhaseForge-related research direction that is closest to my current experience.

My undergraduate thesis uses LAMMPS and classical interatomic potentials. More recently, I used pretrained CHGNet in a small Al-Co learning project.

I have used an MLIP for inference. I have not trained an MLIP.

## My Direct Research Experience

### Molecular dynamics with LAMMPS

I have developed LAMMPS input scripts for my undergraduate thesis on AlxCoCrFeNi high-entropy alloys.

My simulations include:

- uniaxial tensile deformation;
- generalized stacking-fault energy;
- lattice thermal conductivity;
- phonon density of states;
- mean-square displacement.

Through this work, I have gained practical experience with:

- preparing atomic systems;
- selecting and using an interatomic potential;
- equilibration and simulation settings;
- extracting outputs;
- post-processing results;
- debugging simulation workflows.

### Classical interatomic potentials

My thesis calculations rely on classical interatomic potentials.

At my present level, I understand their practical role as models that provide atomic energies and forces for molecular dynamics.

I do not claim expertise in developing or fitting new classical potentials.

## My Recent MLIP Exploration

### CHGNet

In my Al-Co mini-project, I used a pretrained CHGNet model to calculate static energies for generated alloy configurations.

The important distinction is:

```text
What I did:
used a pretrained MLIP for prediction

What I did not do:
train or develop the MLIP
```

This project helped me understand how an atomistic structure can be passed to a modern learned potential and used to generate energy data.

### Single-point energy prediction

My current Al-Co project evaluates static energies for fixed structures.

I understand that this is more limited than a complete workflow involving:

- structure relaxation;
- validation against higher-fidelity calculations;
- broader structure sampling;
- finite-temperature calculations.

## Classical Potential to MLIP: My Learning Bridge

```text
My thesis experience
Classical potential + LAMMPS
            |
            v
Energy / forces
            |
            v
Molecular dynamics
            |
            v
Mechanical and thermal properties
```

My recent exploration adds:

```text
Atomic structure
      |
      v
Pretrained CHGNet
      |
      v
Static energy prediction
```

A future PhD-level extension would be to learn:

```text
Reference data
      |
      v
MLIP training and validation
      |
      v
Reliable atomistic calculations
      |
      v
Thermodynamic data generation
```

## Concepts I Am Currently Learning

I am developing a basic understanding of:

- machine-learning interatomic potentials;
- training data containing structures, energies, forces, and possibly stresses;
- structure relaxation;
- model validation;
- transferability.

I list these as learning topics, not as existing research expertise.

## Connection to My Previous Work

Several parts of my undergraduate research are potentially useful preparation for future MLIP work:

- I already work with atomic structures.
- I already use interatomic potentials.
- I already analyze energies, stresses, trajectories, and vibrational information.
- I already write and debug simulation scripts.
- I have introductory Python and machine-learning coursework.

Therefore, learning MLIPs would extend an existing computational foundation rather than start from zero.

## What I Want to Learn in a PhD

I would like to learn:

- how MLIPs are trained;
- how training structures are selected;
- how energies and forces are used during training;
- how model accuracy is tested;
- how transferability is evaluated;
- how uncertainty or model reliability is assessed;
- how MLIPs can be used to generate thermodynamic data efficiently.

## Current Limits

I do not currently claim experience in:

- training CHGNet, MACE, or another MLIP;
- generating DFT training datasets;
- MLIP hyperparameter optimization;
- systematic MLIP benchmarking;
- uncertainty estimation for MLIPs;
- high-throughput MLIP workflows.

## Research Potential I Hope This Shows

My strongest preparation is the ability to build and troubleshoot atomistic workflows.

The MLIP direction interests me because it builds directly on that experience while introducing modern machine-learning methods and a possible bridge to computational thermodynamics.
