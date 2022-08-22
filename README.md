# Universally Hard Hamiltonian Cycle Problem Instances
This repository contains the source code and the data used for the paper "Universally Hard Hamiltonian Cycle Problem Instances"

## Running the code
To be able to run the code you will need [scale build tool](https://www.scala-sbt.org).

- In the root of the folder run `sbt run`
- It then prompts you `Multiple main classes detected. Select one to run:`
- Press `2` and then press `Enter` to run the experiment

## Dataset
The dataset of 91,000 random graphs of v=14 can be accessed at [indexed-14-node-test-set](src/main/resources/indexed-14-node-test-set).
The files are named `{index}.json` going from 0 to 90999. For each possible edge density [0-91] there are 1000 graphs and the filenames
are ordered by graph density.

## Images
**Performance of 6 algorithms on the 91,000 graphs in the dataset, compared with the top instances evolved via a PPA algorithm.**

![recursions](images/figure_2.png)

**The hardest non-hamiltonian instance on the right with the hardest hamiltonian instances on the left.**
![recursions](images/graphs.png)