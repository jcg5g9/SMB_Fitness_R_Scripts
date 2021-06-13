# SMB_Fitness_R_Scripts
Exploring the effects of hybridization and introgression on longevity, age structure, and productivity in admixed streams of the Neosho Smallmouth Bass range

# Aim 1 - Sample Sizes
## File: SMB_Fitness_Sample_Size_Analysis.Rmd

Purpose: Here I am determining the my sample sizes and plotting them across different rivers, sexes, genetic ID, etc.

### Data used:
#### All working data


# Aim 2 - Individual Growth
## File: SMB_Fitness_Growth.Rmd

Purpose: Here I am developing von Bertalanffy growth curves for the overall sample set and for three genetic groups (pure Northern, pure Neosho, and admixed) within my admixed populations. I am aiming to determine whether there are differences in growth rate between pure Northern, Neosho, or admixed individuals. 

### Data used:
#### All working data

# Aim 3 - Genotype Analysis
## File: SMB_Fitness_STRUCTURE.Rmd

Purpose: Here I am plotting results from the program STRUCTURE, which assesses genetic composition of individual fish based on genotypes from 14 microsatellite markers.

### Data use:
#### Genotype data for 117 individuals over 14 microsatellite loci

# Aim 4 - Admixture Analysis on a geographic gradient
## File: SMB_Fitness_Geo_Admix.Rmd

Purpose: Here I am determining whether there are relationships between the proportion of Northern (invasive) ancestry in samples as they go further down river (starting from the put out point at Deep Ford Access (DFA)). I specifically want to test whether the proportion of Northern SMB ancestry increases with increasing distance from DFA, and I split these analyses up by river (I analyze big sugar and elk river separately). I look at 1) the proportion of Northern ancestry per individual moving downstream, and the proportion of individuals of a given hybrid status at the group level.

# Aim 5 - Heterozygosity-fitness correlations
## File: SMB_Fitness_HFC.Rmd

Purpose: Here I am testing for heterozygosity-fitness correlations between standardized multi-locus heterozygosity (sMLH), calculated in the package inbreedR, and body condition of fish as a proxy for fitness, calculated as mass (g) divided by tl^3. I am specifically testing for any significant correlation between heterozygosity in fitness, whether positive (hybrid vigor) or negative (hybrid breakdown)

### Data use:
#### Genotype data for 117 individuals over 14 microsatellite loci, mass data, and total length data, also data for 20 reference northern and 20 reference Neosho populations

# Aim 6 - Founder effects
# SMB_Fitness_Founder_Effects

Purpose: Here I am testing whether there is evidence of a founder effect on Northern Smallmouth Bass within the Neosho range by examining four genetic diversity metrics between Northern Smallmouth Bass and a Northern reference population. Specifically, I am calculating allelic richness, observed heterozygosity, expected heterozygosity, and the inbreeding coefficient (fis).

### Data use:
#### Genotype data for 20 reference Northern populations and Northern assigned samples within the Neosho range
