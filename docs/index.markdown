---
layout: default
---

This page is a currated list of custom Python modifiers of file readers developed as an extension to [OVITO](https://www.ovito.org/). Each modifier listed here is developed and maintained by members of the community. Please contact social@ovito.org to have your extension reviewed and added to the list. 

## Getting started
To install a Python extension in OVITO Pro run:
```bash
ovitos -m pip install --user git+[GitHub-URL].git
```
from the `ovitos` command line interpreter. 
To install an extension in a standalone Python or Conda environment
```bash
pip install --user git+[GitHub-URL].git
```
command can be used.

Please visit our online documentation for information on installing, running, or developing a OVITO extension.

# Python Modifier

| [Generate random solution](https://github.com/nnn911/GenerateRandomSolution) | Python modifier to change the particle type values to create a random solution of a given composition. | ![pyiron file reader](./media/modifier/generateRandomSolution.png){:width="100%"} |


# Python File Reader

| [pyiron file reader](https://github.com/nnn911/pyironFileReader) | File reader for the h5 data containers written by [pyiron](https://pyiron.org/). | ![pyiron file reader](./media/fileReader/pyironFileReader.png){:width="100%"} |