
# Custom codes for the JARBS-GNR paper 
This page explains custom codes used in the paper "Long-read metagenomics using National genomic surveillance integrating standardized quantitative susceptibility testing clarifies antimicrobial resistance in Enterobacterales" by Shizuo Kayama#†, Koji Yahara#†, Yo Sugawara†, Sayoko Kawakami, Kohei Kondo, Hui Zuo, Shoko Kutsuno, Norikazu Kitamura, Aki Hirabayashi, Toshiki Kajihara, Hitomi Kurosu, Liansheng Yu, Masato Suzuki, Junzo Hisatune, and Motoyuki Sugai†



The following figures were created using the custom codes as explained below
- Fig. 7: Geographical distribution of blaIMP-1, blaIMP-6, and blaNDM genes stratified by replicon type and species carrying the plasmids.

- Fig. S23: Relationship between specimen sources, STs, and the number of strains 
  harboring a blaIMP-1 or blaIMP-6 gene.
  
- Fig. S24: Region, species, antimicrobial susceptibility profiles, replicon type, plasmid size, and resistance genes detected across the complete sequences of plasmids harboring
  (a) blaIMP-1 and (b) blaIMP-6, respectively
  
- Fig. S25: Relationship between replicon type and plasmid size for the complete
  sequences of plasmids harboring blaIMP-1, blaIMP-6, and blaNDM-5, respectively
  
  

This page explains the custome codes according to the guildeline "For manuscripts utilizing custome algorithms or software that are central to the research and no yet described in published literature" of Nature Research.

This page is written based on "Code and Software Submission Checklist" of Nature Research.

## System requirements 
- R and Rstudio

  - packages
    - readr
    - scatterpie
    - tidyverse
    - ggplot2
    - ComplexHeatmap
    - circlize

- python

  - packages
    - jupyterlab
    - pandas
    - seaborn
    - numpy
    - scipy
    - matplotlib





#### Any required non-standard hardware

None for the custom codes.



## Instruction for use

Please go to the directory of each figure, and execute the code.


------
##### Fig. 7: Geographical distribution of blaIMP-1, blaIMP-6, and blaNDM genes stratified by replicon type and species carrying the plasmids.

- Fig.7.Rmd
  - (expected run time: within a minute)


##### Fig. S23: Relationship between specimen sources, STs, and the number of strains harboring a blaIMP-1 or blaIMP-6 gene.
- Fig.S23.Rmd
  - (expected run time: within a minute)

##### Fig. S24: Region, species, antimicrobial susceptibility profiles, replicon type, plasmid size, and resistance genes detected across the complete sequences of plasmids harboring (a) blaIMP-1 and (b) blaIMP-6, respectively
- Fig.S24.Rmd
  - (expected run time: within a minute)

##### Fig. S25: Relationship between replicon type and plasmid size for the complete sequences of plasmids harboring blaIMP-1, blaIMP-6, and blaNDM-5, respectively
- FigS25.ipynb
  - (expected run time: within a minute)

