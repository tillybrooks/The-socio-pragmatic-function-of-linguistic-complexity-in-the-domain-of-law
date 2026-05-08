# The socio-pragmatic function of linguistic complexity in the domain of law

Code and data for _The socio-pragmatic function of linguistic complexity in the domain of law_ (Brooks & Hawkins 2026), _Proceedings of the 48th Annual Meeting of the Cognitive Science Society_.

## Repo Structure
- analysis/
  - materials used for statistical analysis and to generate figures
- data/
  - results from the experiment
- experiment/
  - code for web-based experiment and stimuli
- paper/
  - materials used for drafting paper
 
## Re-run analysis
You can re-run the analysis used in this paper with the following:
```
cd analysis
quarto render analysis.qmd
```
this requires quarto, and the following packages: tidyverse, jsonlite, lme4, lmerTest, emmeans, ggthemes, and ordinal

## Run experiment
The code and materials used to run the experiment can be found in the experiment directory.  Run legal_drafting_experiment.html to re-run the experiment.
