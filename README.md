# Image Scoring Results
(* note that the position angle reported in the fit_summaries.txt is "west of south", and depends on the pre-rotaion of the image and inclination angle)

Scoring Restults:
- Score_run1: fit 3958 hi, non scan-avg data, without theory error
- Score_run2: fit scan-avg data, without theroy error (in progress)
- Score_run3: fit scan-avg data, with theroy error    (cancelled)

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


