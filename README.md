# The Rhythms of Transient Relationships: Allocating time between weekdays and weekends
---

Data and Jupyter notebook with analysis for the aforementioned paper

## Description of the data and file structure

There are four data files

- `sourceUK.csv` contains mobile calla data for [a study](https://doi.org/10.1016/j.evolhumbehav.2010.08.005) conducted by Sam Roberts and Robin Dunbar in the UK.
- `sourceIT.csv` contains mobile call data for the [MTL study](https://doi.org/10.1140/epjds/s13688-016-0064-6) in Italy.
- `transientsUK.csv` contains a collection of transient relationships in the UK, following the criteria described [here](https://doi.org/10.1038/s41598-023-32206-2).
- `transientsIT.csv` contains the information for the transient relationships in Italy.


## Variables used
All data files use the same names for variables.

- `ego`: identifier for ego
- `alter`: identifier for alter
- `time`: timestamp for the phone call 


## Code/Software

There is a jupyter notebook for replication purposes. It can produce the results found in [this](https://doi.org/10.48550/arXiv.2305.14737) paper.
