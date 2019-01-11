# Image Scoring Results
(* note that the position angle reported in the fit_summaries.txt is "west of south", and depends on the pre-rotaion of the image and inclination angle)

Scoring Restults:
- Score_run1: fit 3958 hi non-scan-avg data
- Score_run2: fit 3958 hi scan-avg data
- Score_run3: fit 3958 hi scan-avg data, with both M/D (Gaussian) prior and PA (linear) prior
- Score_run4: fit 3958 hi scan-avg data, with both M/D (linear) prior and PA (linear) prior
- Score_run5: fit 3958 hi scan-avg data, with M/D (linear) prior only
- Score_run6: fit 3958 hi scan-avg data, with PA (linear) prior only [in progress]
- Score_run_3597_hi: fit 3601 hi scan-avg data [in progress]
- Score_run_3598_hi: = Score_run2
- Score_run_3600_hi: fit 3601 hi scan-avg data [in progress]
- Score_run_3601_hi: fit 3601 hi scan-avg data [in progress]

(list of simulations for each scoring is provided in the teamwork notebook)



Under each Scoring folder, the structure looks like:

GRMHD classification:
- IHARM
- BHAC
- KORAL
- HARM (Provided by Koushik, scored in Score_run1)
- time-averaged (provided by Monika, scored in Score_run1)

flow-type classification:
- SANE
- MAD

electron-thermodyanmics classification:
- m_1_1_x (x= Rhigh = 1, 10, 20, 40, 80, 160)


