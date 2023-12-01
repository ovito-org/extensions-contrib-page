---
layout: default
---

This page provides a curated list of useful Python extensions for [OVITO](https://www.ovito.org/), e.g., new [modifiers](https://ovito.org/docs/dev/python/introduction/custom_modifiers.html), [file readers](https://ovito.org/docs/dev/python/introduction/custom_file_readers.html), and [viewport layers](https://ovito.org/docs/dev/python/introduction/custom_overlays.html). These extensions have been developed and contributed by independent members of the OVITO user community. They are hosted in external code repositories, which are maintained by their respective authors.

Please see each extension's documentation or the [OVITO manual](https://ovito.org/docs/dev/reference/pipelines/modifiers/python_script.html#installing-python-based-extensions-for-ovito-with-pip) for installation instructions. Most extensions can be used with *OVITO Pro* and the standalone *OVITO Python Module* (version 3.9 or later). 

## How to submit your extension

If you would like your own extension to be added to this list by the OVITO team, please write to [social@ovito.org](mailto:social@ovito.org). Alternatively, you can open an [issue](https://github.com/ovito-org/extensions-contrib-page/issues) or submit a [pull request](https://github.com/ovito-org/extensions-contrib-page/pulls) to the [GitHub repository](https://github.com/ovito-org/extensions-contrib-page).

# Modifiers

## Atomistic Reverse Monte-Carlo

Generate bulk crystal structures with target Warren-Cowley parameters.

[https://github.com/killiansheriff/AtomisticReverseMonteCarlo](https://github.com/killiansheriff/AtomisticReverseMonteCarlo)

![Atomistic Reverse Monte-Carlo](./media/modifier/atomisticReverseMonteCarlo.png){:width="50%"}

## Calculate bond angles at particle

Outputs the angles between all pairwise combinations of bonds at one particle.

[https://github.com/ovito-org/CalculateBondAnglesAtParticle](https://github.com/ovito-org/CalculateBondAnglesAtParticle)

![Calculate bond angles at particle](./media/modifier/calculateBondAnglesAtParticleModifier.png){:width="50%"}

## Denoise particle positions

Wrapper for the "Score-based denoising for atomic structure identification" method presented in [this arXiv preprint](https://arxiv.org/abs/2212.02421) and implemented [here](https://github.com/LLNL/graphite/).

[https://github.com/nnn911/ScoreBasedDenoising](https://github.com/nnn911/ScoreBasedDenoising)

![Denoise particle positions](./media/modifier/scoreBasedDenoising.png){:width="50%"}

## Display Lammps log

Display the Lammps log file alongside your structure data in OVITO Pro.

[https://github.com/nnn911/DisplayLammpsLog/](https://github.com/nnn911/DisplayLammpsLog/)

![Display Lammps log](./media/modifier/displayLammpsLog.png){:width="50%"}

## Generate random solution

Randomly assigns types to particles to create a solution with given composition.

[https://github.com/nnn911/GenerateRandomSolution](https://github.com/nnn911/GenerateRandomSolution)

![Generate random solution](./media/modifier/generateRandomSolution.png){:width="50%"}

## Warren-Cowley short-range order parameters

Calculates the Warren-Cowley short-range order parameters.

[https://github.com/killiansheriff/WarrenCowleyParameters](https://github.com/killiansheriff/WarrenCowleyParameters)

![Warren-Cowley short-range order parameters](./media/modifier/warrenCowleySRO.png){:width="50%"}

# File Readers

## Pyiron file reader

Reads HDF5 data containers written by [pyiron](https://pyiron.org/).

[https://github.com/nnn911/pyironFileReader](https://github.com/nnn911/pyironFileReader)

![pyiron file reader](./media/fileReader/pyironFileReader.png){:width="50%"}

# Viewport Layers

## Data table plot

Include plots generated from data tables from your pipeline in your image or animation rendered with OVITO Pro.

[https://github.com/ovito-org/DataTablePlotOverlay.git](https://github.com/ovito-org/DataTablePlotOverlay.git)

![data table plot overlay](./media/viewportLayers/dataTablePlotOverlay.png){:width="50%"}

## Measure Distances And Angles

Measure both distances and angles between particles and display them as a layer in the viewport.

[https://github.com/nnn911/DistancesAndAnglesOverlay](https://github.com/nnn911/DistancesAndAnglesOverlay)

![measure distances and angles overlay](./media/viewportLayers/measureDistancesAndAngles.png){:width="50%"}
