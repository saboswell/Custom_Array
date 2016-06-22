Planning on using Custom Array for 90K chip

Suggested by custom array: 

SP6 truncated promoter - insert - BsrDI sequence
GAAGCGAGGATCAACT_insert_region_CATTGCGTGAACCGA

Amplify with custom array defaults

CATACGATTTAGGTGACACTATAGAAGCGAGGATCAACT: Sp6 truncated promoter
GAGCTTCGGTTCACGCAATG: Rev+BsrDI sequence 


WANT to be able to amplify pools of 

1) ERCC_list - for spike ins					2,813 probes
2) galaxy_Neg600 - for long gene analysis		10,743 probes
3) control_100bp_50ovlp.out						2,668 probes
4) set1_200_100bp_50ovlp.out					18,963 probes
5) set201_450_100bp_50ovlp.out					23,488 probes
6) set451_700_100bp_50ovlp.out					22,406 probes

8919 spare probes - to use I modified set1_200 as marked below

You can replace number 4 with the two new files:  set1_200_basic & set1_200_extra - they should be amplified together as one pool
