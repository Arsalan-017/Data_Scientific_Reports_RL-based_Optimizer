This repository contains statistical data related to the mitigation of tumor cell population through SMC, smooth SMC, PPO and Smooth SMC-based PPO algorithms, utilized in the following article: "Development of Novel Reinforcement Learning-Based Optimizer to Impede Tumor Growth via Radiochemotherapy". The data is collected through MATLAB simulations. The simulation files are provided in following separate repositries: 

1) https://github.com/Arsalan-017/Tumor-Mitigation-using-SMC-and-Smooth-SMC
2) https://github.com/Arsalan-017/Tumor_Mitigation_PPO
3) https://github.com/Arsalan-017/Tumor_Mitigation_SSMC-PPO


Contents of Dosage_CSV
The file: Dosage_CSV contians initial conditions of states T and N, at which the considered algorithms have been simulated to record the data of total administered dosages of radiation and chemotherapeutic drug for tumor mitigation, throughout the therapy. 

Contents of Duration_CSV
The file: Duration_CSV contains the data regarding the initial conditions and observed duration taken by the proposed smooth SMC-based PPO algorithm to decimate tumor cell population.

Contents of Duration_Other_Algos_CSV
The file: Duration_Other_Algos_CSV contains the data regarding the reported therapy duration taken by numerous control algorithms proposed in recent scientific articles to mitigate tumor cell population. The data also provides the name of the algorithm alongwith the reference details. 

Contents of statistical_analysis.m
The file: statistical_analysis.m utilizes the data collected in files: Dosage_CSV, Duration_CSV and Duration_Other_Algos_CSV and performs the ann-Whitney U test on the collected data t prove statistically that which of the considered algorithms reduces treatment dosages and therapy time in comparison to others.
