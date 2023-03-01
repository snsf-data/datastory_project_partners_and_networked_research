# More networked research thanks to project partners: a look at the first five years

**Since 2017, project partners can contribute to specific aspects of research projects supported by the SNSF's Project funding scheme. How often are project partners involved? Are there differences between research areas? In which countries are project partners based?**

[English](https://data.snf.ch/stories/project-partners-and-networked-research-en.html)\
[German](https://data.snf.ch/stories/projektpartnerschaften-und-vernetzte-forschung-de.html)\
[French](https://data.snf.ch/stories/partenaires-de-projet-et-recherche-en-reseau-fr.html)

**Author(s)**: Simon Gorin

**Publication date**: 01.03.2023

### Data description

The data used in this data story are available in the folder `data`. The data are split into two files. The first file (`data.csv`) contains information about the 4366 funded grants included in the analysis. The second file (`success_rate_anonymized_data.csv`) contains anonymized aggregated data used in the last section of the story on success rate. Here follows a description of the variables included in these two files.

#### Data set 1: `data.csv`

This data set contains information about funded grants as described in the data story. Each line represent a person involved in the research project. Each funded grant is identified with the variable `snf_grant_number`. Please note thtat some variables are grant-specific and other are person-specific. Here follows a description of grant-specific variables:

-   `snf_grant_number`: the number of the grant used at the SNSF (can be used to search grant at <https://data.snf.ch/grants>)
-   `year`: year in which decisions on most grants of a call are made (it normally means the year in which a grant was approved)
-   `research_area`: the SNSF distinguishes three major research domains (humanities and social sciences, mathematics, natural and engineering sciences, and biology and medicine)
-   `amount_granted`: amount approved for the grant

Here follows a description of person-specific variables:

-   `role`: the role of the person in the application (Applicant, Co-applicant or Projektpartner)
-   `research_institution`: Swiss research institution or university where the grant will largely be carried out according to the application (for more details, see: <https://data.snf.ch/about/glossary#researchinstitution>)
-   `research_institution_type`: type of research institution
-   `country`: country where the researcher is based
-   `iso_code`: ISO code of the country where the researcher is based
-   `continent`: continent of the country where the researcher is based
-   `partner_budget`: amount from the amount granted devoted to the project partner
-   `world_region`: region of the world where the researcher is based (see the data story for more details)
-   `person_id`: unique identifier

#### Data set 2: `success_rate_anonymized_data.csv`

This data set contains anonymized aggregated data about success rate for proposals described in the data story. Each row represent a single application and here follows a description of the included variables:

-   `grand_id`: anonymized grant identifier
-   `is_approved`: whether the proposal has been approved for funding (TRUE is yes and FALSE is no)
-   `research_area`: the SNSF distinguishes three major research domains (humanities and social sciences, mathematics, natural and engineering sciences, and biology and medicine)
-   `n_partners`: numbers of project partners included in the proposal, as described in the data story
