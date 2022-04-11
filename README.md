#### Replication package for the paper:

*Search Budget in Multi-Objective Refactoring Optimization: a Model Based Empirical Study*\
by Daniele Di Pompeo and Michele Tucci

#### How to generate the tables and figures in the paper
Initialize the python execution environment:
```bash
git clone https://github.com/SEALABQualityGroup/2022-seaa-replication-package
cd 2022-seaa-replication-package
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Generate tables and figures:
```bash
python HV_table_and_timeline.py
python time_and_algo_comparison.py
python superpareto_scatter.py
```
