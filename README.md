# LinkageMappingWorkshop
In this directory I have scripts and data for the JCU Acquaculture Linkage Mapping workshop held between the 8th and 11th of October, 2023.

The requirements for this workshop are:
- R version 4+
- R Studio
- R packages (tidyverse, knitr, ggpubr, LinkageMapView)
- Visual Studio Code (VSC)
- Visual Studio Code Remote-SSH extension
- LepMap3

The majority of the workshop is run from your institution's High Performance Research Cluster, using VSC as an IDE to both write and submit scripts.

We will also use R locally in RStudio to produce some of the results.

In the future I do plan to run R as well remotely. 

There are two main things you need to download and/or bring to follow along:

- The workshop 'script(s)' (either in Rmd or knitted Html format) [LinkageMappingWorkshop.Rmd]
- The example data and/or your own data already in the required LepMap input [input_fam1.txt]

In case you do not have the data in the required output, I have a (messy) R markdown file that will guide you through the step to download your data from plink's .bed format to the lepmap format. Please note that this script is not generalised to any input data and currently contains references to some of the student's data. If you want to use it for yourself you will have to adjust the ID of parents and families to be used for linkage mapping. [ConvertToLepmap.Rmd]



