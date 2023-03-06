CATI 1.0 Public Use Variable Information

This file contains data used to construct national and state values of the Child and Adolescent Thriving Index 1.0. 

More information on how the index is constructed is available at https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2797715. Readers interested in how the methodology was derived can find more information at https://link.springer.com/article/10.1007/s12187-022-09962-0.

Each row represents a single area-year combination (using statename year variables). The file is cleaned to focus on information most pertinent to a general audience. Most of the variables used in the sensitivity analyses have been removed.

Brief description of variables:

areatype: 1 for national values, 2 for state values, missing for racial/ethnic subpopulation values
subpop: for areatype= missing, has a code for indigenous (AIAN), Asian, Black, Hispanic, and White national estimates

myindex_ind is the CATI 1.0 index score using the preferred methodology
- corresponding _ctxt, ind_alt, and ctxt_alt are different formulations (largely arrive at similar results)
- aec_score_total is the KIDS COUNT score for comparable analyses


Key to understanding variables
- variables with “rank” are annual state rankings based on the value scores, otherwise if not denoted with rank they represent the value for that area-year combination
- variables with “aec” are components of the Annie E. Casey KIDS COUNT Index
- variables with “mine” are components of the CATI 1.0 index -> use the _mn (mean) variables, not the _se (standard error) variables
