# AccentASR_HumanPerception

Detailed Info for Accent-Combined Corpus Creation in paper: https://arxiv.org/abs/2104.04627


## Three Source Accented Corpora:

#### 1. Mozilla Common Voice corpus


#### 2. Singapore English National Speech corpus

From Part2 - Channel 0 of the corpus, we add all the speech data from 33 randomly sampled speakers to our Accent-Combined training set. Similarly, we add all the speech data from 4 randomly sampled speakers (different to the ones selected for training set) to our Accent-Combined development set.


#### 3. L2-Arctic corpus


## Table of Component:

| Attempt | Subsampled Train (Hour)| Subsampled Dev (Hour) | Train/Dev Ratio|
| -------------| ------------- | ------------- | ------------- |
| Mozilla Common Voice | 22.84h  | 4.29h  | 5:32: 1  |
| Singapore English National Speech | 24.24h  | 4.80h  | 5.05 : 1  |
| L2-Arctic | 22.84h  | 4.23h  | 5.40 : 1  |
| TOTAL | 69.92h  | 13.32h  | 5.25: 1  |
