READ ME

IYS eDNA data 2020-2019


Files: 
2020_2019_IYS_GoA_filtered_eDNA_detections:
Data table that contains operational taxonomic units (OTUs) in rows and library ID in columns. Value is the sum of reads in the sample assigned to the approproate OTU from all three amplicons (16S chordate, 16S cephalopods, COI salmonids).

Abbeviations: 
COI= mitochondrially encoded cytochrome c oxidase I 
16S_Ceph= motochondrially encoded 16S rRNA genes Cephalopods
16S_Chord= motochondrially encoded 16S rRNA genes Chordates
NTC= No template control
ATC: Artificial template control

2020_2019_sample_info.csv:
Metadata to link sample to expedition and  sampling site


Background:
Water collected with Nislkin bottle from 2-3m. 2L filtered onto Sterivex column for each replicate.
Filters flash frozen. DNA extracted from filters using DNeasy kits (QUIAGEN).
16S and COI rRNA gens were amplified with PCR and sequenced on Illumina MiSeq platform using SE at 300 cycles.
Reads were processed using obitools (https://pythonhosted.org/OBITools/welcome.html) and queired against nt using BLASTn.
Reads were assigend to OTU using MEGAN (https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/algorithms-in-bioinformatics/software/megan6/).
Results were filtered using a cuttoff of >/=10 reads for positive detection.
Detectons of obvious contaminations belonging to human or food waste (sheep, pig, chicken, cow) as well as artificail positive controls were removed.
For detailed information contact Dr. Christoph Deeg: chdeeg@mail.ubc.ca
