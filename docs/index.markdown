---
layout: default
---

This page provides a curated list of useful Python extensions for [OVITO](https://www.ovito.org/), e.g., new [modifiers](https://ovito.org/docs/dev/python/introduction/custom_modifiers.html) and [file readers](https://ovito.org/docs/dev/python/introduction/custom_file_readers.html). These extensions have been developed and contributed by independent members of the OVITO user community. They are hosted in external code repositories, which are maintained by their respective authors.

Please see each extension's documentation or the [OVITO manual](https://ovito.org/docs/dev/reference/pipelines/modifiers/python_script.html#installing-python-based-extensions-for-ovito-with-pip) for installation instructions. Most extensions can be used with *OVITO Pro* and the standalone *OVITO Python Module* (version 3.9 or later). 

## How to submit your extension

If you would like your own extension to be added to this list by the OVITO team, please write to [social@ovito.org](mailto:social@ovito.org). Alternatively, you can open an [issue](https://github.com/ovito-org/extensions-contrib-page/issues) or submit a [pull request](https://github.com/ovito-org/extensions-contrib-page/pulls) to the [GitHub repository](https://github.com/ovito-org/extensions-contrib-page).

# Modifiers

## Calculate bond angles at particle

Outputs the angles between all pairwise combinations of bonds at one particle.

[https://github.com/ckalcher/CalculateBondAnglesAtParticle](https://github.com/ckalcher/CalculateBondAnglesAtParticle)

![Calculate bond angles at particle](./media/modifier/calculateBondAnglesAtParticleModifier.png){:width="50%"}

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
