# Ontology of Self-Reference in Neuroimaging
This dataset, compiled up to November 1, 2023, standardizes neuroimaging data on self-referential behaviors and neural responses from 4054 participants across 117 studies. It reflects a broad demographic range and includes data from 15 countries.

## Data Description
Participants include 2406 women, with ages from adolescents to the elderly, and 1061 individuals with mental health conditions like Generalized Anxiety Disorder, Major Depressive Disorder, and Schizophrenia.

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

### `suppl_material/`
The `suppl_material` folder is home to supplementary documents and files that support the database. 
#### Included Files
- `Self_Ref_Article_Info.csv`: Basic information on selected literature, such as author, journal, sample size.
- `Self_Ref_Operationalization.csv`: Operational definitions of the self-referential effect in the selected literature, including experimental stimuli, design, tasks, etc.
- `Codebook_Self_Ref_Article_Info.csv`: Codebook for `Self_Ref_Article_Info.csv`.
- `Codebook_Self_Ref_Operationalization.csv`: Codebook for `Self_Ref_Operationalization.csv`.
- `自我参照_文章信息.csv`: Basic information on selected literature, such as author, journal, sample size.
- `自我参照_操作化定义.csv`: Operational definitions of the self-referential effect in the selected literature, including experimental stimuli, design, tasks, etc.
- `手册_自我参照_文章信息.csv`: Codebook for `自我参照_文章信息.csv`.
- `手册_自我参照_操作化定义.csv`: Codebook for `自我参照_操作化定义.csv`.

## Contact
- Prof. Hu Chuan-Peng (hcp4715@hotmail.com)
- Shu-ting Sun (Version 2, sunshuting19@163.com)
- Shanshan Zhu (Version 3, zhushanshan0717@gmail.com)

## Contribution
1. `[2021.11-]`Hu Chuan-Peng: Overall scheme design, data verification, organization, and paper writing and revision
2. Shu-ting Sun  (2021.11-2022.12)
   Data collection and proofreading, summarization, data analysis, and paper writing and revision 
3. Nan Wang (2021.11-2022.12)
   Data collection and proofreading, summarization and collation, and paper writing and revision 
4. Jia-hui Wen (2021.11-2022.07)
   Data collection
5. Shanshan Zhu (2023.01-)
   Data collection and proofreading, summarization and collation, and paper writing and revision
6. Jia-qi Wu (2023.01-)
   Data collection and proofreading, summarization and collation
7. Jian Xiao (2023.07-2023.11)
   Data collection and proofreading, database verification, data analysis
8. Ya-qi Li (2023.07-)
   Database collection and proofreading
