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
- Sun Shutting, Wang Nan, Wen Jiahui, et al. Neuroimaging cognitive ontology dataset of self-reference [J/OL]. China Science Data, 2023, 8(3). (2023-07-27).[DOI: 10.11922/11-6035.csd.2022.0047.zh](https://doi.org/10.11922/11-6035.csd.2022.0047.zh)

- Hu, C., Di, X., Eickhoff, S. B., Zhang, M., Peng, K., Guo, H., & Sui, J. (2016). Distinct and common aspects of physical and psychological self-representation in the brain: A meta-analysis of self-bias in facial and self-referential judgements. Neuroscience & Biobehavioral Reviews, 61, 197–207. https://doi.org/10.1016/j.neubiorev.2015.12.003

## Repository Structure

```
.
├── 1_Reference
│ ├── About.txt
│ ├── ...
│ └── 补充材料2:编码手册.pdf
│
├── 2_Literature_Search
│ ├── About.txt
│ ├── Keyword_search.txt
│ └── Literature_Search.docx
│
├── 3_Article_Screen
│ ├── Endnote_files
│ │ ├── 3_1_Self-ref_hcp
│ │ ├── ...
│ │ └── add_Neurosy+Query_0710
│ ├── Literature_neuroQuery.docx
│ ├── Search_flow.png
│ └── self_ref_screen_flow.docx
│
├── 4_Data_Extraction
│ ├── 4_1_Codebook
│ ├── 4_2_Coordinate
│ └── 4_3_Manual
│
├── 5_Analysis
│ ├── 5_3_ThirdTrial
│ └── About.txt
│
├── 6_Reports
│ ├── 6_1_Project_reports [slides]
│ └── 6_2_Preprint
│ 
├── 7_Dataset
│ ├── Ont_Heal_Self_foci_v1
│ └── self_foci_psy
│
├── .gitignore
├── LICENSE
└── README.md (Overall project documentation)

```

## Contact
- Prof. Hu Chuan-Peng (hcp4715@hotmail.com)
- Shanshan Zhu (Version 3, zhushanshan0717@gmail.com)
- Shuting Sun (Version 2, sunshuting19@163.com)

## Contributors
- **[2021.11-]** **Hu Chuan-Peng**: Overall scheme design, data verification, organization, and paper writing and revision.
- **[2021.11-2022.12]** **Shu-ting Sun**: Data collection and proofreading, summarization, data analysis, and paper writing and revision.
- **[2021.11-2022.12]** **Nan Wang**: Data collection and proofreading, summarization and collation, and paper writing and revision.
- **[2021.11-2022.07]** **Jia-hui Wen**: Data collection.
- **[2023.07-2023.11]** **Jian Xiao**: Data collection and proofreading, database verification, data analysis.
- **[2023.01-]** **Shanshan Zhu**: Data collection and proofreading, summarization and collation, and paper writing and revision.
- **[2023.01-]** **Jia-qi Wu**: Data collection and proofreading, summarization and collation.
- **[2023.07-]** **Ya-qi Li**: Database collection and proofreading.