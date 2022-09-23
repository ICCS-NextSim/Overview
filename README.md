# neXtSIM-4-Antarctica

Goals 
------------------
1) Run existing Artic NextSim-ERA5-GLORYS setup for 1 Jan 2018-1 February 2018 on Mahuika-cluster. 
2) Create test suite in Python. Suite should at very least contain binary comparison with existing file. 
3) Optional. Replace GLORYS ocean forcing with SOSE (Southern Ocean State Estimate). 


Methods
------------------
1) A neXtSIM singularity image was created from neXtSIM original docker image. Now the model can be used in NZ's cluster
2) neXtSIM was run in two different machines and its outputs were compared for consistency
3) Adittionally, three simulations were run locally for case study:
- ocean stress only
- ocean and thermal forcing
- ocean, thermal and wind stress


Results 
------------------
1) Run existing Artic NextSim-ERA5-GLORYS setup for 1 Jan 2018-1 February 2018 on Mahuika-cluster. 
2) Create test suite in Python. Suite should at very least contain binary comparison with existing file. 
3) Optional. Replace ERA5 atmospheric forcing with SOSE atmospheric forcing. 
