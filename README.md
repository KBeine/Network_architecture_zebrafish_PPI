# Network_architecture_zebrafish_PPI
Network architecture of transcriptomic stress responses in zebrafish embryos

Code for publishing purposes

Network Data for reference in Cytoscape
- Downloaded from Pasan Fernando's figshare:
- https://figshare.com/articles/dataset/Gene_network_module_changes_associated_with_the_vertebrate_fin_to_limb_transition/13589579/1
- Lin_zebrafish_integrated_network.txt was used in sif format to generate .cys formatting to use in Cytoscape

Transcriptomic data and differential gene expression used in this analysis taken from:
- Feugere, L., Silva De Freitas, C., Bates, A., Storey, K. B., Beltran-Alvarez, P., & Wollenberg Valero, K. C. (2025). Data for: Social context prevents heat hormetic effects against mutagens during fish development [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7566285

All code used is in RStudio. Analysis includes:
- Go term analysis to pull out genes related to gene ontology (stress) - Figure 1 and 2
    - Authors: Dr. Lauric Feugere, modified by Dr. Kaylee Beine
- Discriminant function analysis (DFA) graph to show positioning of P, I, H nodes using network statistics from Cytoscape for the network after node assignment by SPSS - Figures 1, 2-5, S1
    - Author: Dr. Kaylee Beine
- Pie chart graph showing percentages of nodes within each of the networks analyzed - Figures 1, 2-5, S1
    - Author: Dr. Kaylee Beine
- Error plot graph showing significant comparisons for network data and DEGs in treatments - Figures 1, 2-5, S1
    - Author: Dr. Kaylee Beine
- Venn diagram showing proportional size of DEGs in treatments - Figure 2
    - Author: Dr. Kaylee Beine
- Co-variation of DEG network parameters and phenotypic outcomes - Figure 6
    - Author: Prof. Katharina C. Wollenberg Valero
- Chord diagrams showing shared phenotypic effects of DEGs by treatment and network node category - Figure 7
    - Author: Dr. Kaylee Beine
- Phenotypic effects of DEGs by treatment comparison - Figure 8
    - Author: Prof. Katharina C. Wollenberg Valero

Notes
- Ensure all your .csv files are located in your working directory.
- Set your working directory with "setwd("path/to/your/data")". Replace "your_data.csv" with the actual filenames.
- You can extend this template by copying more blocks from your script.
- Use ggsave() or pdf() within R code chunks if you need to output static plots.
