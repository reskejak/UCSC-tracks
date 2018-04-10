# UCSC-tracks
https://genome.ucsc.edu/ (mm10)

* "My Data" --> "Track Hubs" --> "My Hubs"

* paste-in the following URLs for various track data visualizations

* Note: each URL must be entered separately, since many of the hubs call the same data files and thus cannot be combined

## CURRENT "MOST USEFUL" HUBS

#### ATAC-seq data, normalized by fragments per million reads, displayed as log-likelihood ratio signal to noise

separated by each genotype group compared to WT:

https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/ATAC/reps-vs-WT/hub_flG.txt
https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/ATAC/reps-vs-WT/hub_flfl.txt
https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/ATAC/reps-vs-WT/hub_het.txt

aggregate multiWig track of all samples:

https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/ATAC/aggregate/hub_logLR.txt

#### RNA-seq data, normalized by reads per million mapped reads (RPM)

separated by each genotype group compared to respective WT samples:

https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/RNA/reps-vs-WT/hub_flG.txt
https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/RNA/reps-vs-WT/hub_homo.txt
https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/RNA/reps-vs-WT/hub_het.txt

aggregate multiWig track of all samples:

https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/RNA/aggregate/hub.txt



## OTHER MISCELLANEOUS HUBS

#### ATAC-seq data, normalized by fragments per million reads, displayed as fold-enrichment signal to noise

note: tends to be a bit noisy, for cleaner results see log-LR normalized tracks

"aggregate" = multiWig of all samples in experiment

"replicates" = fully separated by each genotype group with biological replicates overlayed

https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/ATAC/aggregate/hub.txt
https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/ATAC/replicates/hub.txt

#### ATAC-seq data, normalized by fragments per million reads, displayed as log-likelihood ratio signal to noise

fully separated by each genotype group with biological replicates overlayed

https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/ATAC/replicates/hub_logLR.txt

#### RNA-seq data, normalized by reads per million mapped reads (RPM)

fully separated by each genotype group with biological replicates overlayed

https://raw.githubusercontent.com/reskejak/UCSC-tracks/master/RNA/replicates/hub.txt
