# econ5200-lab10-causal-logic

I need help writing a project description for my data science lab.
**Important Rule:** Do NOT generate any Python code for me.

**What I did in this lab:**
* Diagnosed a regression in which adding a control caused by both the
  treatment and the outcome moved the estimate from -0.012 to -0.593
  and raised R-squared to 0.585, when the true effect
  was zero
* Showed that a control measured before treatment can still bias an
  estimate: -0.211 against a true effect of zero
* Separated a total effect (4.034, truth 4.0) from a direct effect
  through a mediator (1.018, truth 1.0)
* Compared the LaLonde job-training experiment's benchmark of
  $1,794 with an observational estimate using CPS controls:
  -$8,498 before covariate adjustment and $699 after
* Used a dag_utils.py module that finds valid adjustment sets from a DAG
* Had an AI propose the controls for a job-training study and checked its
  set against the study's DAG: its first set gave 3.62 against a
  true effect of 4.0; after I revised my prompt once, 4.05

**Please write a README.md entry including:**
1. Project Title: Causal Logic and DAGs: Diagnosing Bad Controls
2. Objective: one sentence
3. Methodology: Bullet points of technical steps
4. Key Findings: Summary of results
Write it plainly, in the first person. No words like 'robust',
'comprehensive' or 'leverage'. Use only the numbers I gave you.
