# information-theoretic-prompts

## Overview

This is a companion repository to the paper "An Information-Theoretic Approach to Prompt Engineering".

## Setup
To clone repo, run:
```bash
git clone https://github.com/tsor13/information-theoretic-prompts
```

## Authors
This code is provided by the authors. For any questions, please reach out to Taylor Sorensen at tsor1313@gmail.com.

## Usage

To generate your own experiment for comparing prompt templates with mutual information, run
```python
python3 run_experiment.py --dataset squad --n 64 --seed 0 --lm_model 'gpt2-xl'
```

![Simulated Data](plots/simulated0.png?raw=true "Simulated Data")
