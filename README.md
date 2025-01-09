README
Jacinta Kong

# Part 1
This experiment aimed to characterise the effects of rearing temperature on the life history of *Gryllodes sigillatus*, the banded cricket. This experiment is Part 1 of the paper.
`tpc_mass.xslx` is the raw data associated with part 1. The metadata is described within the HTML of part 1.

# Part 2
This experiment aimed to characterise the effects of rearing temperature on the reproductive output of *Gryllodes sigillatus*, the banded cricket under common garden conditions. This experiment follows up from Part 1 and uses a subset of temperature treatments from Part 1.
Three datasets (csv) are associated with this experiment. Described below:

1. F1_ParentID - Life history information about the parents

temperature: Rearing temperature (Vevor incubators)
ID_P: Unique identifier for the individual
date_hatched: Date individual hatched
date_start: Date individual was allocated to rearing temperature
date_end: Date individual was removed from experiment (Death, Maturity or Completion)
reason_removed: Reason individual was removed from experiment
date_subadult: Date individual could be identified to sex
sex: Sex of individual
date_adult: Date individual reached instar 8 (adult)
container: Mass (g) of the weighing container
container_adult: Mass (g) of the weighing container and the adult individual
pair: Unique identifier of the mating pair
date_paired: Date cricket was allocated mating pair
excluded: Flag for whether cricket was excluded from analysis
reason_excluded: Reason for why cricket was excluded from analysis
notes: Other observations

2. F1_eggs - Number of eggs laid for each pair every 48h. 

Rows are individual pairs.
Columns are data collection dates

3. F1_hatch - Batches of eggs incubated

date_laid: Date batch of eggs was laid
pair: Unique identifier of the mating pair (parents)
hatching_success: Flag for whether at least one egg hatched
date_hatched: Date first nymph was observed
no_hatchlings: Number of nymphs counted after 2 days of hatching (peat frozen and dried in oven)
notes: Other observations

