# Stability analysis of a Mesh DC microgrid with Adaptive Distributed Droop control and CPLs

This repository was created to store the files related to the above mentioned Article.
The goal is to study and evaluate the stability of a Mesh like DC microgrid with Adaptive Distributed droop control strategy for voltage restoration and power/current sharing in presence of Uncertain CPLs.

Direct current microgrids (DCMGs) have gained interest in the pursuit of achieving higher integration of renewable energy sources (RESs) and improving system resilience and reliability. The highly cooperative nature of these MGs is an advantage in order to maximize the RESs utilization and minimize grid power demand. However, ensuring stable and robust operation in the presence of significant load fluctuations constitutes a major challenge. Overvoltages and overcurrents, among other phenomena related to system stability, deteriorate the power quality and can be prevented with proper analysis. In this regard, numerous research studies have presented proposals related to the achievement of an optimal power distribution among the individual DERs of a DCMG.
However, the stable operation of these MGs still requires further analysis to reach the same level of understanding accomplished in other topologies. Therefore, in this project, a stability analysis for a Mesh like DCMG is presented. This analysis includes the modeling of the system considering a distributed control strategy and the presence of uncertain active loads, and the subsequent formulation of sufficient conditions of load and generation power for robust stability of the DCMG. Finally, the concordance between the results of the circuital simulations and those related to the stability analysis is assessed. Moreover, conclusions about the representation of the microgrid and the optimal tuning of the controller´s gains and parameters are drawn.

### Folders

#### Datasets
In this folder are stored:
+ The .csv files created during the simulations with Simulink
+ Eigenvalues obtained from the presented analysis
+ Equilibrium values of the state variables

#### Scripts
This folder contains the scripts employed during the analysis to:
+ Define the state space matrices and their eigenvalues.
+ Generate the csv files for plotting and analysis.
+ Variables definition for Simulink Enviroment.

#### Simulunk
This folder stores the created Simulink enviroments employing MatLab 2018a.


### Keywords

DC microgrid, Networking microgrid, Constant power load, Adaptive droop control, Robust Stability, Power electronics

### Future Works
Future works that I aim to incorporate to the current project is compared the obtained results using LMI formulations to solve the Lyapunov conditions problem.

### Contact

Feel free to contact me if you have questions, suggestions or comments regarding the article.

Academic email: mcarnaghi@fi.mdp.edu.ar
Personal email: carnaghi.marco@gmail.com
