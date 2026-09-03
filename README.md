# NovCor Manuscript

This repository contains the code and main analysis files used for bioinformatics and data analysis for the manuscript:
"Description of *Corynebacterium nasorum* sp. nov. and *Corynebacterium hallucis* sp. nov. isolated from human nasal passages and skin"

A preprint of this manuscript is available at [bioRxiv](https://www.biorxiv.org/content/10.1101/2024.11.21.624533v1).

See [NovCor_Manuscript](https://klemonlab.github.io/NovCor_Manuscript/) for the rendered version of the code and analysis notebooks, which are organized by method and analysis type. 

The `data/` folder contains all the files related to the analyses performed for the manuscript. The main analyses include:

-   Code for the custom Prokka annotations can be found in [here](https://klemonlab.github.io/NovCor_Manuscript/Methods_Prokka_Annotations.html).

    -   The `data/genomes` folder contains the original `.fasta` files for all genomes used in the analysis, organized in subfolders based on the figures they were used for.
    
    -   The `data/genome_lists` folder contains the lists of genomes used for different analyses, including the 28 proposed *C. nasorum* genomes and the 30 genomes representative of the *C. tuberculostearicum* species complex.

-   Detailed code for the [ANI](https://klemonlab.github.io/NovCor_Manuscript/Methods_ANIs.html) and [dDDH](https://klemonlab.github.io/NovCor_Manuscript/Methods_dDDH.html) analysis.

    -   The `data/pyani-plus` folder contains the results from the ANI analysis.

    -   The `data/GGDC` folder contains the results from the dDDH analysis.

-   Most relevant data relative to construction of phylogenetic and phylogenomic trees:

    -   The `data/phylogenies` folder contains all the files related to phylogenetic and phylogenomic analyses, including alignments and tree files.

-   Analysis performed using anvi'o is documented in [here](https://klemonlab.github.io/NovCor_Manuscript/Methods_Anvio.html).

    -   The `data/anvio-9` folder contains all the files related to anvi'o analyses, including contigs databases, metabolic analysis, and pangenome analysis.
