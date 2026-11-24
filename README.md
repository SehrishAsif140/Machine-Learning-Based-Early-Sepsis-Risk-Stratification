# Machine-Learning-Based-Early-Sepsis-Risk-Stratification
Machine Learning-Based Early Sepsis Risk Stratification Using Structured Clinical Data

# Early sepsis risk stratification (PhysioNet/CinC 2019)
Code for the revised manuscript.
Run order in Colab: S0 (setup), then the analysis cells; N1 to N6 are the revision analyses.
Hospital mapping: patients with Patient_ID <= 20643 are Training Set A, the rest Training Set B (verified against the official files).
Target: t_sepsis = first SepsisLabel=1 hour + 6; target = 1 if 1 <= t_sepsis - Hour <= 6; onset/post-onset rows excluded.
Frozen threshold: 0.281145870686. Random seed: 2026.
Data: https://physionet.org/content/challenge-2019/1.0.0/ (not included in this repository).
