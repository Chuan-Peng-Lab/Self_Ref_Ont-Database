# Ontological dataset of Self-related Studies in Neuroimaging

This dataset, compiled up to August 1, 2025, standardizes metadata extracted from neuroimaging studies that employed self-referential encoding tasks. In total, the dataset includes 136 studies involving 4,694 participants from 17 countries.

## Data Description

Data were compiled from 136 neuroimaging studies that employed the self-referential encoding task ([Rogers et al, 1977](doi.org/10.1037/0022-3514.35.9.677)). The dataset includes a total of 4,696 participants (2,697 females), spanning a wide age range from adolescents to elderly adults. Participants include both healthy individuals and patients with psychiatric disorders, allowing for comparisons across clinical and non-clinical populations. In Version 4, we expanded the literature search using broader and more targeted keyword combinations related to self-referential processing. As a result, 26 additional studies were included, featuring both psychiatric populations and healthy controls performing self-referential tasks.

## Version History

- **Version 4 (Aug 01, 2025)**: Expanded search terms; added studies involving psychiatric populations.
- **Version 3 (Jan 22, 2024)**: Includes adolescents and elderly, enhanced disease info in the Codebook.
- **Version 2 (Nov 28, 2022)**: Adult population focus, meta-analysis of healthy subjects.
- **Version 1 (Jul 25, 2022)**: Initial operational definitions and article information.

## Software Used

- Used Zotero for literature organization and Python(v3.12.11) for analysis (Versions 4).
- Used Zotero for literature organization and MATLAB R2021A for analysis (Versions 3).
- Used Endnote for literature storage and R and MATLAB R2018B for analysis (Versions 1-2).


## Related Publications

Sun, Wang, Wen, & Hu. (2023).  A dataset of cognitive ontology for neuroimaging studies of self-reference. China Scientific Data, 8(3), 175–189. https://doi.org/10.11922/11-6035.csd.2022.0047.zh

Hu, C., Di, X., Eickhoff, S. B., Zhang, M., Peng, K., Guo, H., & Sui, J. (2016). Distinct and common aspects of physical and psychological self-representation in the brain: A meta-analysis of self-bias in facial and self-referential judgements. Neuroscience & Biobehavioral Reviews, 61, 197–207. https://doi.org/10.1016/j.neubiorev.2015.12.003

## Related Code
https://github.com/Chuan-Peng-Lab/Self_Ref_Ont-Database

## Folder Structure

### `Self_foci_raw/`
This subfolder contains fMRI coordinate results extracted from each literature source included in the study. Each file within the folder is named after the corresponding study and formatted according to the BrainMap.

#### Example Files
- `Bach_2021_EurArchPsychiatryCliNeurosci.txt`: This file includes fMRI results from [Bach et al. (2021)](doi.org/10.1007/s00406-021-01307-2), with coordinates data of the brain regions activated during self-referential tasks.

### `Suppl_Data_Results_for_Sun_etal_2023/`
The `Suppl_Data_Results_for_Sun_etal_2023` subfolder contains supplementary data, scripts, and results for [Sun et al 2023](doi.org/10.11922/11-6035.csd.2022.0047.zh).

### Database encoding related files
- `Self_Ref_Article_Info.csv`: Basic information on selected literature, such as author, journal, sample size.
- `Self_Ref_Operationalization.csv`: Operational definitions of the self-referential effect in the selected literature, including experimental stimuli, design, tasks, etc.
- `Codebook_Self_Ref_Article_Info.csv`: Codebook for `Self_Ref_Article_Info.csv`.
- `Codebook_Self_Ref_Operationalization.csv`: Codebook for `Self_Ref_Operationalization.csv`.
- `自我参照_文章信息.csv`: Basic information on selected literature, such as author, journal, sample size.
- `自我参照_操作化定义.csv`: Operational definitions of the self-referential effect in the selected literature, including experimental stimuli, design, tasks, etc.
- `手册_自我参照_文章信息.csv`: Codebook for `自我参照_文章信息.csv`.
- `手册_自我参照_操作化定义.csv`: Codebook for `自我参照_操作化定义.csv`.

```

.
├── Self_foci_raw
│ ├── Abraham_2013_Brain_Imaging_Behav.txt
│ ├── ...
│ └── Zhang_2015_NeuroimageClin.txt
│
├── Suppl_Data_Results_for_Sun_etal_2023
│ ├── Suppl_Data_Results
│ │ ├── celebrity-nonPerson_cFWE.nii
│ │ ├── close-celebrity_cFWE.nii
│ │ ├── close-nonPerson_cFWE.nii
│ │ ├── Figure4_data.csv
│ │ ├── Interrater_Reliability_Raw.csv
│ │ ├── self_all_cFWE.nii
│ │ ├── Self_all.txt
│ │ ├── Self_celebrity.txt
│ │ ├── Self_close.txt
│ │ ├── Self_nonPerson.txt
│ │ ├── Suppl_RNotebook.nb.html
│ │ └── Suppl_RNotebook.Rmd
│ └── Supplementary_Materials.docx
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

```

## Contact
- Prof. Hu Chuan-Peng (hcp4715@hotmail.com)
- Shan-Shan Zhu (*Version 3 & 4*, zhushanshan0717@gmail.com)
- Shu-Ting Sun (*Version 1 & 2*, sunshuting19@163.com)


## Contributors
- **[2021.11-present]** **Hu Chuan-Peng**:  Project design; data verification and management; manuscript writing and revision.
- **[2023.01-present]** **Shan-shan Zhu**: Data collection and proofreading; data summarization and organization; manuscript writing and revision.
- **[2025.03-present]** **Xue-Yang Zhu**: Data collection and proofreading.
- **[2025.03-present]** **Xin-Yan Li**: Data collection and proofreading.
- **[2025.03-present]** **Zhao-Li Fan**: Data collection and proofreading.
- **[2024.07-2024.11]** **Si-Yu Wu**: Data collection and proofreading.
- **[2023.01-2023.12]** **Jia-Qi Wu**: Data collection and proofreading, summarization and collation.
- **[2023.07-2023.09]** **Ya-Qi Li**: Database collection and proofreading.
- **[2021.11-2022.12]** **Shu-Ting Sun**: Data collection and proofreading, summarization, data analysis, and paper writing and revision.
- **[2021.11-2022.12]** **Nan Wang**: Data collection and proofreading, summarization and collation, and paper writing and revision.
- **[2021.11-2022.07]** **Jia-Hui Wen**: Data collection.
- **[2023.07-2023.11]** **Jian Xiao**: Data collection and proofreading, database verification, data analysis.
