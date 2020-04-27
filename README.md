# points-of-dispense
## Decision Analytics for Business and Policy final project
#### Maxwell Kennady, Nora Murray, Elizabeth Speigle

This repository contains jupyter notebooks for running two versions of a facility location problem for three scenarios:



- Scenario 1 - Global:
    - Templates for minimizing total distance and minimizing maximum distance with a given number of PODs:
        - pod.ipynb 
        - pod_minmax.ipynb
    - Sensitivity analysis on the number of PODs to open:
        - pod_varysites.ipynb (creates pickle pod_open_total2)
        - pod_minmax_varysites.ipynb (creates pickle pod_open_minmax2)

- Scenario 2 - Flooding - Sensitivity analysis on the number of PODs to open:
    - pod_varysites_flood.ipynb  (creates pickle pod_flood_total2)
    - pod_minmax_varysites_flood.ipynb  (creates pickle pod_flood_minmax2)

- Scenario 3 - Anthrax - Sensitivity analysis on the number of PODs to open:
    - pod_varysites_anthrax.ipynb (creates pickle pod_anthrax_total2)
    - pod_minmax_varysites_anthrax.ipynb (creates pickle pod_anthrax_minmax2)

- Analysis:
    - Analysis_1.ipynb includes comparisons of average and maximum distance traveled for each scenario and model, distributions of population-weighted distances for each scenario, and charts of the number of times each POD is selected in the global scenario
    - Analysis_2.ipynb includes 
    
- Data folder: 
    - BG_master.xlsx contains block group information, with detailed descriptions in the data dictionary.
    - OD_Pairs_Distances.csv contains the distances in miles and driving time between each POD and each block group.
    - Data Dictionary.xlsx contains detailed descriptions of each data field.
    
- Pickles created by notebooks above:
    - pods_open_total2
    - pods_open_minmax2
    - pods_flood_total2
    - pods_flood_minmax2
    - pods_anthrax_total
    - pods_anthrax_minmax2
	
	
- This repository also contains an ArcGIS file geodatabase, which does not need to be run and is only included for reference. It also contains two jpeg files, which were created using ArcGIS.