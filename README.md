# Image Scoring Results
(* note that the position angle reported in the fit_summaries.txt is "west of south", and depends on the pre-rotaion of the image and inclination angle)

Scoring Restults:
- Score_run1: fit 3958 hi, non scan-avg data, without theory error
- Score_run2: fit scan-avg data
- Score_run3: fit scan-avg data, with both M/D and PA priors
- Score_run4: fit scan-avg data, with M/D priors (in progress)

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


