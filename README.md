# The evolution of compositional hierarchical structure in the lab: experimental data sets 
[![DOI](https://zenodo.org/badge/147381554.svg)](https://zenodo.org/badge/latestdoi/147381554)


This text file explains the supporting data files containing the languages that evolved in the iterated learning experiments 1 and 2 in [Saldana et al (2019)](https://academic.oup.com/jole/article/4/2/83/5499169?guestAccessKey=0cec6c43-beeb-47d4-b586-d8897ce444a4). You can find the code used to run the experiments in _Experiments.zip_[`Python 2.7`, `PsychoPy v1.82.01`] and the picture frames necessary to display the event stims split into two files: _stimFrames1.zip_ and _stimFrames2.zip_.

`SKTS2018_languages` contains 8 spreadsheets. Each spreadsheet belongs to a transmission chain.  Sheets that belong to Experiment 1 are named `Exp1` and  those that belong to Experiment 2, are named `Exp2`. Descriptions of the column headings for each sheet are as follows: 

- `Meaning` : the meaning the descriptions refer to. (PFV stands for perfective or terminated aspect; its absence, indicate imperfective or ongoing aspect.) 

- `Initial Language` : the randomised initial language used to train the first generation of the transmission chain 

- `Generation 1` : the language produced by the first generation in the transmission chain. Generation 1 is trained on a randomly selected set of items from the initial language (44 in Exp1 and 40 in Exp2).
 
- `Generation 2 to 8` : the language produced by the corresponding generation (2 to 8) in the transmission chain. Each generation is trained on a randomly selected set of items from the previous generation (44 in Exp1 and 40 in Exp2).
