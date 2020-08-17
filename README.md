## *SARS-CoV-2 contributes to altering the post-transcriptional regulatory networks across human tissues by sponging RNA binding proteins and micro-RNAs*

**Rajneesh Srivastava** 1, Swapna Vidhur Daulatabad1, Mansi Srivastava1*, Sarath Chandra Janga1,2,3*

1. Department of Biohealth Informatics, School of Informatics and Computing, Indiana University Purdue University, 719 Indiana Ave Ste 319, Walker Plaza Building, Indianapolis, Indiana 46202
2. Center for Computational Biology and Bioinformatics, Indiana University School of Medicine, 5021 Health   Information and Translational Sciences (HITS), 410 West 10th Street, Indianapolis, Indiana, 46202
3. Department of Medical and Molecular Genetics, Indiana University School of Medicine, Medical Research and Library Building, 975 West Walnut Street, Indianapolis, Indiana, 46202

### Correspondence can be addressed to :  
Mansi Srivastava (Email: mansriva@iupui.edu)
or
Sarath Chandra Janga (Email: scjanga@iupui.edu)

School of Informatics and Computing
Indiana University Purdue University
719 Indiana Ave Ste 319
Indianapolis, Indiana 46202


## Abstract
The outbreak of a novel coronavirus SARS-CoV2 responsible for COVID-19 pandemic has caused worldwide public health emergency. Due to the constantly evolving nature of the coronaviruses, SARS-CoV-2 mediated alteration on post-transcriptional gene regulation across human tissues remains elusive. In this study, we systematically dissected the crosstalk and dysregulation of human post-transcriptional regulatory networks governed by RNA binding proteins (RBPs) and micro-RNAs (miRs), due to SARS-CoV-2 infection. We uncovered that 13 out of 29 SARS-CoV-2 encoded proteins directly interact with 51 human RBPs of which majority of them were abundantly expressed in gonadal tissues and immune cells. We further performed a functional analysis of differentially expressed genes in mock-treated versus SARS-CoV-2 infected lung cells that revealed enrichment for immune response, cytokine-mediated signaling, and metabolism associated genes. This study also characterized the alternative splicing events in SARS-CoV-2 infected cells compared to control demonstrating that skipped exons and mutually exclusive exons were the most abundant events that potentially contributed to differential outcomes in response to viral infection. Motif enrichment analysis on the RNA genomic sequence of SARS-CoV-2 clearly revealed the enrichment for RBPs such as SRSFs, PCBPs, ELAVs, and HNRNPs illustrating the sponging of RBPs by SARS-CoV-2 genome. A similar analysis to study the interactions of miRs with SARS-CoV-2 revealed functionally important miRs that were highly expressed in immune cells, suggesting that these interactions may contribute to the progression of the viral infection and modulate host immune response across other human tissues. Given the need to understand the interactions of SARS-CoV-2 with key post-transcriptional regulators in the human genome, this study provides a systematic analysis to dissect the role of dysregulated post-transcriptional regulatory networks controlled by RBPs and miRs, across tissues types during SARS-CoV2 infection.


## MAIN FIGURES
### Figure Legends:

**Figure 1.** Protein-protein interaction network analysis suggest an immediate interaction of human RBPs with SARS-CoV2 viral proteins (A) An integrated SARS-CoV-2 – human RBP interaction network. We obtained the MS-based SARS-CoV-2 viral protein to human protein interaction network established in HEK293 cells and integrated with 1st neighbor interacting RBPs (obtained from BioGRID). (B) Protein abundance of SARS-CoV2 interacting RBPs across human tissues. Expression data were obtained from human protein map and row normalized. SARS-CoV-2 proteins were color coded and highlighted in the network. 

**Figure 2.** Differential expression analysis of mock treated versus SARS-CoV-2 infected primary human lung epithelial cells. (A) Bar-plot illustrating the significant pathways obtained from GO-term based functional grouping of differentially expressed genes (DEGs, at 5% fdr) using ClueGO analysis (Cytoscape plugin) (B) Row normalized expression profile of differentially expressed RBPs in mock treated and SARS-CoV-2 infected primary human lung epithelial cells (in biological triplicates).

**Figure 3.** Alternative splicing events during SARS-CoV2 infection. (A) Bar plot showing the genes (RBP encoding genes in blue) exhibiting alternative splicing during SARS-CoV-2 infection in primary human lung epithelial cells (at 5% fdr). (B) Clustered GO-term network obtained from function annotation analysis and grouping of the GO-term for the genes exhibiting alternative splicing using ClueGo (cytoscape plugin). Significant clustering (adj. p < 1e-05) of functional groups were color coded by functional annotation of the enriched GO-biological processes, with size of the nodes indicating the level of significant association of genes per GO-term, were shown.

**Figure 4.** Motif enrichment analysis reveals potential human RBPs titrated by SARS-CoV-2 viral genome. (A) Violin plot shows the statistically significant (p-value < e-05) preferential binding profile of RBP motifs (sorted by frequency of binding and greater than 10 sites) across the SARS-CoV-2 viral genome (length normalized) identified using FIMO. (B) Hierarchically clustered heatmap showing the protein abundance (row normalized) of RBPs across tissues.

**Figure 5.** SARS-CoV-2 genome titrates the abundance of functionally important miRs in human tissue (A) Violin plot shows the statistically significant (p-value < e-05) preferential binding profile of miR- motifs (sorted by frequency of binding >15 sites) across the SARS-CoV-2 viral genome (length normalized) identified using FIMO. (B) Hierarchically clustered heatmap showing the log10 expression (CPM, row normalized) of miRs across tissues. (C) Bar-plot illustrating the significant biological processes, obtained from gene ontology enrichment based functional grouping of miR target genes (obtained from miRNet). Significant clustering (adj. p < 1e-10) of genes enriched in GO-biological processes generated by ClueGO analysis (Cytoscape plugin).
 
## SUPPLEMENTARY MATERIALS
### Supplementary Figure Legends:

**Figure S1.** Protein-protein interaction network of differentially expressed genes in mock treated versus SARS-CoV-2 infected primary human lung epithelium (NHBE cells) where node size and color show the absolute and relative log2 fold changes, respectively.

**Figure S2.** (A) Violin plot shows the statistically significant (p-value < e-05) preferential binding profile of RBP motifs (sorted by frequency of binding) across the SARS-CoV2 viral genome (length normalized), identified using FIMO (B) Hierarchical clustered heatmap showing the protein abundance (row normalized) of RBPs across tissues.

### Supplementary Table Legends:

**Table S1.** Significant biological pathways obtained from functional annotation analysis of differentially expressed genes (at 5% fdr)  in mock treated versus SARS-CoV-2 infected primary human lung epithelium (NHBE cells) using ClueGO (a cytoscape plugin).

**Table S2.** Identification of alternative splicing events using rMATS (replicate Multivariate Analysis of Transcript Splicing) in mock treated versus SARS-CoV-2 infected primary human lung epithelium (NHBE cells).

**Table S2.** Significant biological pathways obtained from functional annotation analysis of alternatively spliced genes (at 5% fdr) in mock treated versus SARS-CoV-2 infected primary human lung epithelium (NHBE cells) using ClueGO (a cytoscape plugin).

**Table S4.** Preferential binding location of RBP motifs identified by FIMO across the SARS-CoV2 viral genome.

**Table S5.** Preferential binding location of miR-motifs identified by FIMO across the SARS-CoV2 viral genome.

**Table S6.** Significant biological pathways obtained from functional annotation analysis of mir-targeted genes (from mirNet) using ClueGO (a cytoscape plugin).
