# amaze-natural-stories
Materials, data, code for A-maze of Natural Stories talk

Stories and comprehension questions are from https://github.com/languageMIT/naturalstories

Distractor generation was done using https://vboyce.github.io/Maze/

## Contents

Prep_code: Get the text ready for maze, also get frequencies and surprisals
- make_unigrams.py calculate unigram frequencies from the Gulordava training data
- nat_stories_prep.Rmd various states of text manipulation, reading in surprisals
- natural_stories_surprisals.rds
- useful.py

Materials:
- for_ns.js Ibex data file
- natural_stories_sentences.tsv

Data:
- raw_data Ibex results file
- cleaned.rds rectangular data file

Analysis:
- nat_stories has descriptives and error rates
- nat_stories_lms has linear regressions (mostly Bayesian)
- nat_stories_gam has GAM regressions
- read_results.R reads in the Ibex results file and makes cleaned.rds
