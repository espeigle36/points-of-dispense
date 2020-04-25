# points-of-dispense
## Decision Analytics for Business and Policy final project
#### Maxwell Kennady, Nora Murray, Elizabeth Speigle

This repository contains jupyter notebooks for running two versions of a facility location problem for three scenarios:

- Scenario 1 - Global:
    - Templates for minimizing total distance and minimizing maximum distance with a given number of PODs:
        - pod.ipynb 
        - pod_minmax.ipynb
    - Sensitivity analysis on the number of PODs to open:
        - pod_varysites.ipynb
        - pod_minmax_varysites.ipynb

- Scenario 2 - Flooding - Sensitivity analysis on the number of PODs to open:
    - pod_varysites_flood.ipynb
    - pod_minmax_varysites_flood.ipynb

- Scenario 3 - Anthrax - Sensitivity analysis on the number of PODs to open:
    - pod_varysites_anthrax.ipynb
    - pod_minmax_varysites_anthrax.ipynb

- Analysis.ipynb
    - 

- Data folder: 
    - BG_master.xlsx contains block group information, with detailed descriptions in the data dictionary.
    - OD_Pairs_Distances.csv contains the distances in miles and driving time between each POD and each block group.
    - Data Dictionary.xlsx contains detailed descriptions of each data field.