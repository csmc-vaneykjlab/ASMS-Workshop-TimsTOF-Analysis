# Effect on Library Size on Protein Identification and Quantification timsTOF (TimsTOF Pro) by TIMS-DIA-NN
  ## Qin Fu and Niveda Sundararaman, Cedars-Sinai Medical Center

## Introduction
This repository contains the code, results, libraries and metadata information with regards to **Effect on Library Size on Protein Identification and Quantification timsTOF (TimsTOF Pro) by TIMS-DIA-NN** Live demo. 

## Input Files: 
The input files can be downloaded from Panorama Web: https://panoramaweb.org/Instruction/2022%20ASMS%20Workshop/Bruker%20TimsTof%20data/project-begin.view? 

Small library result file: **20221021_SmallLibrary_Clean_Run2_GlabalNomalizationOFF_results.tsv**

Large library result file: **Hela_DIArun2_cleanLargeLibrary_nomralizationOFF_results.tsv**

## Library Files: 
The library files that was used for both the analysis can be downloaded from Panorama Web: https://panoramaweb.org/Instruction/2022%20ASMS%20Workshop/Bruker%20TimsTof%20data/project-begin.view?

Small library File: **_ip2_ip2_data_paser_spectral_library__MacCoss_Hela_10XDDA_iRT_cleaned.tsv**

Large library File: **_ip2_ip2_data_paser_spectral_library__Combined_BrukerHuman_MacossIRT_cleaned.tsv**

## Requirements:
All the data analysis and visualization were done using the R Programming Language (3.6.3 or above). 

R can be downloaded from: https://www.r-project.org/ 

Packages required: 

-dplyr

-tidyverse

-ggplot2

-RColorBrewer

-Hmisc

Installing R packages: https://datatofish.com/install-package-r/ 

##code block for installation of packages

```r
# Install devtools from CRAN
install.packages("dplyr")
install.packages("tidyverse")
install.packages("ggplot2")
install.packages("RColorBrewer")
install.packages("Hmisc")

```

## Set-up using GitHub Repository 

**Step 1**: Download the zip file from this link: https://github.com/csmc-vaneykjlab/ASMS-Workshop-TimsTOF-Analysis/archive/refs/heads/main.zip


**Step 2**: Extract the zip file to the folder of your choice  right click on the downloaded file  extract all  choose location

![image](https://user-images.githubusercontent.com/32958585/200050513-17744389-460c-49e1-9143-581f402e2afd.png)


**Step 3**: 
A.	Open R studio instance and go to the sessions tab to set working directory 
![image](https://user-images.githubusercontent.com/32958585/200050547-aa92e9ad-cb9c-4538-bf3c-a031005836c1.png)


B.	Choose the src folder under the extracted folder on step 2 :  

![image](https://user-images.githubusercontent.com/32958585/200050579-19983f10-3352-4b03-baa5-114388526aa6.png)

C.	On the files pane, on the right hand side. Double click the paser_data_analysis_small.Rmd to open 

![image](https://user-images.githubusercontent.com/32958585/200050606-4b4d806e-440b-4355-9f67-703ceb6a8bf1.png)

 

And then, follow along with the demo. 

Thank you!

