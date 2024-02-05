# Ontological dataset of Self-related Studies in Neuroimaging
This dataset, compiled up to November 1, 2023, standardizes meta data extracted from neuroimaging studies that employed self-referential encoding task. In total, this dataset include 117 studies (4054 participants from 15 countries).

## Data Description
Participants (N = 4054, 2406 females) range from adolescents to the elderly. In version 3, we also included 1061 individuals with mental health conditions like Generalized Anxiety Disorder, Major Depressive Disorder, and Schizophrenia.

## Version History
- **Version 3 (Jan 22, 2024)**: Includes adolescents and elderly, enhanced disease info in the Codebook.
- **Version 2 (Nov 28, 2022)**: Adult population focus, meta-analysis of healthy subjects.
- **Version 1 (Jul 25, 2022)**: Initial operational definitions and article information.

## Software Used
- Used Endnote for literature storage and R and MATLAB R2018B for analysis (Versions 1-2).
- Used Zotero for literature organization and MATLAB R2021A for analysis (Versions 3).

## Related Publication
Sun Shutting, Wang Nan, Wen Jiahui, et al. Neuroimaging cognitive ontology dataset of self-reference [J/OL]. China Science Data, 2023, 8(3). (2023-07-27).[DOI: 10.11922/11-6035.csd.2022.0047.zh](https://doi.org/10.11922/11-6035.csd.2022.0047.zh)

## Repository Structure
### `Self_foci_raw/`
This folder contains fMRI coordinate results extracted from each literature source included in the study. Each file within the folder is named after the corresponding study and formatted according to the BrainMap.
#### Example Files
- `Bach_2021_EurArchPsychiatryCliNeurosci.txt`: This file includes fMRI results from the study by Bach et al. (2021), published in the European Archives of Psychiatry and Clinical Neuroscience, detailing the brain regions activated during self-referential tasks.

### `Suppl_Materials_Version2/`
The `Suppl_Materials_Version2` folder contains supplementary materials for a meta-analysis conducted using the version 2 database. This collection supports the results of the meta-analysis by providing detailed data, visualizations, and analysis scripts.

### Database encoding related files
- `Self_Ref_Article_Info.csv`: Basic information on selected literature, such as author, journal, sample size.
- `Self_Ref_Operationalization.csv`: Operational definitions of the self-referential effect in the selected literature, including experimental stimuli, design, tasks, etc.
- `Codebook_Self_Ref_Article_Info.csv`: Codebook for `Self_Ref_Article_Info.csv`.
- `Codebook_Self_Ref_Operationalization.csv`: Codebook for `Self_Ref_Operationalization.csv`.
- `自我参照_文章信息.csv`: Basic information on selected literature, such as author, journal, sample size.
- `自我参照_操作化定义.csv`: Operational definitions of the self-referential effect in the selected literature, including experimental stimuli, design, tasks, etc.
- `手册_自我参照_文章信息.csv`: Codebook for `自我参照_文章信息.csv`.
- `手册_自我参照_操作化定义.csv`: Codebook for `自我参照_操作化定义.csv`.

├── Self_foci_raw
│   ├── Abraham_2013_Brain Imaging Behav.txt
│   ├── ...
│   └── Zhang_2015_NeuroimageClin.txt
│   
├── Suppl_Materials_Version2
│   ├── Suppl_Data_Results_Version2
│   │   ├── celebrity-nonPerson_cFWE.nii
│   │   ├── close-celebrity_cFWE.nii
│   │   ├── close-nonPerson_cFWE.nii
│   │   ├── Figure4_data.csv
│   │   ├── Interrater_Reliability_Raw.csv
│   │   ├── self_all_cFWE.nii
│   │   ├── Self_all.txt
│   │   ├── Self_celebrity.txt
│   │   ├── Self_close.txt
│   │   ├── Self_nonPerson.txt
│   │   ├── Suppl_RNotebook.nb.html
│   │   └── Suppl_RNotebook.Rmd
│   └── Supplementary_Materials_Version2.docx
│
├── 手册_自我参照_操作化定义.csv
├── 手册_自我参照_文章信息.csv
├── 自我参照_操作化定义.csv
├── 自我参照_文章信息.csv
├── Codebook_Self_Ref_Article_Info.csv
├── Codebook_Self_Ref_Operationalization.csv
├── Self_Ref_Article_Info.csv
├── Self_Ref_Operationalization.csv
│
└── README.md (Overall project documentation)

## Contact
- Prof. Hu Chuan-Peng (hcp4715@hotmail.com)
- Shu-ting Sun (Version 2, sunshuting19@163.com)
- Shanshan Zhu (Version 3, zhushanshan0717@gmail.com)

## Contributors
- **[2021.11-]** **Hu Chuan-Peng**: Overall scheme design, data verification, organization, and paper writing and revision.
- **[2021.11-2022.12]** **Shu-ting Sun**: Data collection and proofreading, summarization, data analysis, and paper writing and revision.
- **[2021.11-2022.12]** **Nan Wang**: Data collection and proofreading, summarization and collation, and paper writing and revision.
- **[2021.11-2022.07]** **Jia-hui Wen**: Data collection.
- **[2023.07-2023.11]** **Jian Xiao**: Data collection and proofreading, database verification, data analysis.
- **[2023.01-]** **Shanshan Zhu**: Data collection and proofreading, summarization and collation, and paper writing and revision.
- **[2023.01-]** **Jia-qi Wu**: Data collection and proofreading, summarization and collation.
- **[2023.07-]** **Ya-qi Li**: Database collection and proofreading.