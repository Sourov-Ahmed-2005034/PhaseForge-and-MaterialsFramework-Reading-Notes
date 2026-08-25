# Thermodynamics and CALPHAD: Current Learning Notes

## Why This Topic Is Here

My undergraduate research is mainly atomistic. I first got to know about calculation of phase diagram (CALPHAD) in the Metallurgy course I took in my 6th semester (L-2, T-2) and became interested in CALPHAD while exploring how phase stability and microstructure can be modeled.

I have recently used pycalphad for an introductory binary phase-equilibrium project. I have not performed a full CALPHAD assessment or fitted thermodynamic database parameters.

## Concepts I Am Comfortable Explaining at a Basic Level

### Gibbs free energy

At constant temperature and pressure, Gibbs free energy is commonly written as:

```text
G = H - TS
```

The relative Gibbs free energies of phases are important for determining equilibrium phase stability.

My present understanding is conceptual rather than expert-level thermodynamic modeling.

### Phase equilibrium

Phase equilibrium describes the condition in which the phases present can coexist without a net thermodynamic driving force for further change.

My practical exposure comes from using an existing thermodynamic database with pycalphad to calculate binary phase behavior.

### CALPHAD

CALPHAD stands for CALculation of PHAse Diagrams.

My current understanding is that CALPHAD uses mathematical thermodynamic descriptions of phases together with assessed model parameters to calculate equilibrium behavior.

I have used CALPHAD software as a learner. I have not yet developed or optimized a CALPHAD database.

### Thermodynamic database and TDB

A thermodynamic database stores the model information and parameters used for phase-equilibrium calculations.

Through pycalphad, I have begun learning how a TDB file is used as an input for calculations.

I am not yet experienced in creating a complete TDB assessment from experimental and computational data.

### Formation-energy idea

In my Al-Co learning project, I calculated a constrained static energy difference relative to selected elemental references:

```text
Delta E =
E_alloy - x_Al E_Al - x_Co E_Co
```

I use this only as an educational energetic descriptor.

I do not interpret it as a complete finite-temperature Gibbs free energy or a complete phase diagram.

## What My Current Projects Have Taught Me

My current learning path is:

```text
Atomistic energy
      |
      v
Reference energy comparison
      |
      v
Basic energetic stability idea
```

My pycalphad project introduced a different level:

```text
Thermodynamic database
      |
      v
Equilibrium calculation
      |
      v
Phase behavior versus temperature and composition
```

The gap between these two workflows is one of the main areas I would like to study in graduate research.

## Questions I Want to Learn to Answer

During a PhD, I would like to understand:

- How are Gibbs-energy models for real alloy phases selected?
- How are CALPHAD parameters fitted?
- How are experimental and computational data combined?
- How are reference states treated consistently?
- How can atomistic calculations contribute useful data to thermodynamic modeling?
- How is uncertainty in a thermodynamic model evaluated?

## Current Limits

I do not currently claim experience in:

- full thermodynamic assessment;
- CALPHAD parameter optimization;
- compound-energy-formalism model development;
- uncertainty propagation in CALPHAD;
- automated thermodynamic database generation.

These are future learning directions.

## Connection to My Research Potential

My atomistic background gives me experience generating and analyzing computational materials data. My recent pycalphad work has motivated me to learn how such data can be connected to phase-equilibrium modeling.

That atomistics-to-thermodynamics connection is the main reason this topic is relevant to my PhaseForge preparation.
