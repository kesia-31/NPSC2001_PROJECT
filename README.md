# NPSC2001_PROJECT
This repository contains all the code made for my NPSC2001 Project 'Reservoir Computing for Non-Linear Time Series Analysis in the Grains Industry'.

--------- Files
juvenile_ESN - Contains the very first working implementation of an Echo State Network
juvenile_ESN_ver2 - Contains small edits and improvements to original 'juvenile_ESN' notebook 
rc_test1_silo - Using the rudimentary ESN implementation in 'juvenile_ESN_ver2' on actual data sourced from the SILO Dataset
optimised_rc - An optimised form of earlier ESN implementation.
rc_test2_silo - Using the more optimised ESN implementation in 'optimised_rc' on actual data sourced from  
the SILO Dataset 
rc_test3_silo - Applying the optimised ESN implementation in 'optimised_rc' on multiple locations from each of the GRDC Sub-Regions
rc_test4_silo - Fixed mistakes in ESN implementation of 'rc_test3_silo' and applied edited ESN to SILO Data. First attempt of a freerun prediction. 
rc_test5_silo - Updated calling functions for testing and implemented working freerun prediction.  
rc_test6_silo- Implemented calculating of the 'complexity' measure. Tested against Merredin data and toy systems.
sprott_test7 - Introduced the Sprott System B and investigated the complexity measure for this toy system against Merredin data.
rc_cleaned_8 - Contains the final, working implementation of the Echo State Network which was then applied to various locations. 
sprott_test9 - Attempts to reconstruct dynamical systems begin in this notebook.
This is a preliminary attempt to use the pecuzal_embedding package to perform Pecuzal Embedding and reconstruct the Spott B System
sprott_test10 - Manual reconstruction of the Sprott B system and Merredin weather system through Taken's Embedding Theorem 
advanced_plotting - Contains relevant plotting and results required for Final Report and Presentation


--------- Dependencies
All notebooks are self-contained, with the exception of 'advanced_plotting', which requires the download of 'DATAFILES' to be able to generate the Map-based plots. 



