<!-- badges: starts -->
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
<!-- badges: end -->

# MetDatOpPp
Metabolomics Datasets for Optimization of Pre-Processing from [*Metabolomics Workbench*](https://www.metabolomicsworkbench.org/) and [*MetaboLights*](https://www.ebi.ac.uk/metabolights/index) repositories or from original R packages. FIMS or semi-targeted experiments are not considered. All data were collected from LC-HRMS instruments (except MTBLS 2483 - LC-LRMS).
All missing values were coded as gaps. Non-informative columns and samples were preliminarily deleted. The table contains key information about datasets: file name, source link, label for LC/MS run order, number of batches, total number of factors and two columns with structure of factors.

File Name | Source | Run Order | Batch | Total Factors | Numeric Factors | Categorical Factors | Number of: Samples/Features/QCs
--------- | ------ | --------- | ----- | ------------- | --------------- | ------------------- | -------------------------------
[MTBLS 146](https://github.com/plyush1993/MetDatOpPp/blob/main/MTBLS%20146.csv) | [Link](https://www.ebi.ac.uk/metabolights/MTBLS146/descriptors) | + | 2 | 3 | 2 | 1 (5 levels) | 217/1312/57
[MTBLS 664 C18 neg](https://github.com/plyush1993/MetDatOpPp/blob/main/MTBLS%20664%20C18%20neg.csv) | [Link](https://www.ebi.ac.uk/metabolights/MTBLS664/descriptors) | + | 4 | 1 | 0 | 1 (3 levels) | 456/5142/30
[MTBLS 664 HILIC pos](https://github.com/plyush1993/MetDatOpPp/blob/main/MTBLS%20664%20HILIC%20pos.csv) | [Link](https://www.ebi.ac.uk/metabolights/MTBLS664/descriptors) | + | 4 | 1 | 0 | 1 (3 levels) | 456/6906/30
[MTBLS 665 C18 neg](https://github.com/plyush1993/MetDatOpPp/blob/main/MTBLS%20665%20C18%20neg.csv) | [Link](https://www.ebi.ac.uk/metabolights/MTBLS665/descriptors) | + | 2 | 2 | 0 | 2 (4, 2 levels) | 192/6671/12
[MTBLS 665 HILIC pos](https://github.com/plyush1993/MetDatOpPp/blob/main/MTBLS%20665%20HILIC%20pos.csv) | [Link](https://www.ebi.ac.uk/metabolights/MTBLS665/descriptors) | + | 2 | 2 | 0 | 2 (4, 2 levels) | 192/8197/12
[MTBLS 2483](https://github.com/plyush1993/MetDatOpPp/blob/main/MTBLS%202483.csv) | [Link](https://www.ebi.ac.uk/metabolights/MTBLS2483/descriptors) | + | 15 | 3 | 1 | 2 (2, 2 levels) | 1447/83/163
[MW 387](https://github.com/plyush1993/MetDatOpPp/blob/main/MW%20387.csv) | [Link](https://www.metabolomicsworkbench.org/data/DRCCMetadata.php?Mode=Project&ProjectID=PR000303) | + | 1 | 1 | 0 | 1 (2 levels) | 276/708/26
[MW 1200 RP](https://github.com/plyush1993/MetDatOpPp/blob/main/MW%201200%20RP.csv) | [Link](https://www.metabolomicsworkbench.org/data/DRCCMetadata.php?Mode=Project&ProjectID=PR000808) | + | 7 | 0 | 0 | 0 | 320/5244/42
[MW 1200 HILIC](https://github.com/plyush1993/MetDatOpPp/blob/main/MW%201200%20HILIC.csv) | [Link](https://www.metabolomicsworkbench.org/data/DRCCMetadata.php?Mode=Project&ProjectID=PR000808) | + | 7 | 0 | 0 | 0 | 319/10371/42
[MW 1682](https://github.com/plyush1993/MetDatOpPp/blob/main/MW%201682.csv) | [Link](https://www.metabolomicsworkbench.org/data/DRCCMetadata.php?Mode=Project&ProjectID=PR001081) | + | 13 | 4 | 2 | 2 (2, 2 levels) | 311/982/63
[MW 1722](https://github.com/plyush1993/MetDatOpPp/blob/main/MW%201722.csv) | [Link](https://www.metabolomicsworkbench.org/data/DRCCMetadata.php?Mode=Project&ProjectID=PR001104) | + | 2 | 2 | 0 | 2 (2, 2 levels) | 110/194/32
[Amide_data WaveICA](https://github.com/plyush1993/MetDatOpPp/blob/main/Amide_data%20WaveICA.rar) | [Link](https://www.sciencedirect.com/science/article/pii/S0003267019301849?via%3Dihub) | + | 4 | 1 | 0 | 1 (2 levels) | 729/6969/85
[Amide_data WaveICA 2.0](https://github.com/plyush1993/MetDatOpPp/blob/main/Amide_data%20WaveICA%202.0.rar) | [Link](https://link.springer.com/article/10.1007%2Fs11306-021-01839-7) | + | 3 | 1 | 0 | 1 (2 levels) | 642/6461/74
[Set_1 BatchCorrMetabolomics](https://github.com/plyush1993/MetDatOpPp/blob/main/Set_1%20BatchCorrMetabolomics.csv) | [Link](https://link.springer.com/article/10.1007%2Fs11306-016-1015-8) | + | 6 | 0 | 0 | 0 | 761/567/51
[OneBatchData batchCorr](https://github.com/plyush1993/MetDatOpPp/blob/main/OneBatchData%20batchCorr.csv) | [Link](https://link.springer.com/article/10.1007%2Fs11306-016-1124-4) | + | 1 | 0 | 0 | 0 | 34/11284/18
[ThreeBatchData batchCorr](https://github.com/plyush1993/MetDatOpPp/blob/main/ThreeBatchData%20batchCorr.csv) | [Link](https://link.springer.com/article/10.1007%2Fs11306-016-1124-4) | + | 3 | 0 | 0 | 0 | 90/11815/48
