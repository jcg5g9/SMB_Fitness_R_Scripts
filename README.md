# SMB_Fitness_R_Scripts
Exploring the effects of hybridization and introgression on longevity, age structure, and productivity in admixed streams of the Neosho Smallmouth Bass range

# Aim 1 - Sample Sizes
## File: SMB_Fitness_Sample_Size_Analysis.Rmd

Purpose: Here I am determining the my sample sizes and plotting them across different rivers, sexes, genetic ID, etc.

### Data used:
#### All working data

# Aim 2 - Tests for Sexual Dimorphism
## File: SMB_Fitness_Sex_Dimorphism.Rmd

Purpose: here I am running  linear models to determine whether covariation between various morphometric traits (standard length, head length, orbital length, body depth) and total length is different between males and females. I want to determine whether males and females are growing differently in any of these traits, which addresses whether they may be sexual selection pressures affecting individual fitness

### Data used:
#### All working data

# Aim 3 - Individual Growth
## File: SMB_Fitness_Growth.Rmd

Purpose: Here I am developing von Bertalanffy growth curves for the overall sample set and for three genetic groups (pure Northern, pure Neosho, and admixed) within my admixed populations. I am aiming to determine whether there are differences in growth rate between pure Northern, Neosho, or admixed individuals. 

### Data used:
#### All working data

# Aim 4 - Genotype Analysis
## File: SMB_Fitness_STRUCTURE.Rmd

Purpose: Here I am plotting results from the program STRUCTURE, which assesses genetic composition of individual fish based on genotypes from 14 microsatellite markers.

### Data use:
#### Genotype data for 117 individuals over 14 microsatellite loci

# Aim 5 - Admixture Analysis on a geographic gradient
## File: SMB_Fitness_Geo_Admix.Rmd

Purpose: Here I am determining whether there are relationships between the proportion of Northern (invasive) ancestry in samples as they go further down river (starting from the put out point at Deep Ford Access (DFA)). I specifically want to test whether the proportion of Northern SMB ancestry increases with increasing distance from DFA, and I split these analyses up by river (I analyze big sugar and elk river separately). I look at 1) the proportion of Northern ancestry per individual moving downstream, and the proportion of individuals of a given hybrid status at the group level.