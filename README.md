# ANVISA_forecast_DT_Raw

# Drug_Reg_ANVISA_DT

*_These analysis are a part of many over the same dataset._*

**Project Status**: [Current status: In progress, completed, etc.]

## **ATTENTION**

> Run the script in a **Python** environment, but use responsably. Mistakes can be commited.
  ### Dependencies (libraries used):
    pandas 2.2.2
    numpy 2.0.2
    nltk 3.9.1
    scikit-learn 1.6.1
    matplotlib 3.10.0
    scipy 1.14.1

  
## Project Overview

This project aims to forecast product registration in Brazilian pharmaceutical market by analyzing Brazilian Health Surveillance Agency (ANVISA) data.

ANVISA DATABASE: Medicines Registered in Brazil

> _"The open drug registration database is a data intelligence project that extracts information from the Datavisa system to list products that have been registered by Anvisa, including those whose registration is already valid or canceled/expired, as reported on the Agency's consultation portal."_

> URL: https://dados.gov.br/dados/conjuntos-dados/medicamentos-registrados-no-brasil

The dataset includes information about:
- 'PRODUCT_TYPE';
- 'PRODUCT_NAME';
- 'PROCESS_END_DATE';
- 'REGULATORY_CATEGORY';
- 'PRODUCT_REGISTRATION_NUMBER';
- 'REGISTRATION_EXPIRATION_DATE';
- 'PROCESS_NUMBER';
- 'THERAPEUTIC_CLASS';
- 'REGISTRATION_HOLDER_COMPANY';
- 'REGISTRATION_STATUS';
- 'ACTIVE_INGREDIENT'.

## Project guideline

- Can we evaluate the tendecies concerning the drug registration?

- Can we predict the the drug registration?

## Project Deliverables

**Data Cleaning and Preprocessing**
> Clean and prepare the data for analysis, handling missing values, inconsistencies, and data formatting.

**Exploratory Data Analysis**
> Conduct exploratory data analysis to identify patterns, trends, and insights from the data.

**Visualization**
> Develop visualizations, such as charts and graphs, to communicate findings effectively and highlight key trends.

**Statistical Analysis**
> Perform statistical analysis to quantify the insights gained from the data.

**Predictive Modeling**
> Develop machine learning models to predict future trends on product releasing.

**Report:**

> Data Cleaning and Preprocessing
>> The columns used for analysis were: 'PROCESS_FINALIZATION_DATE', 'REGULATORY_CATEGORY', 'THERAPEUTIC_CLASS'; Transformed in 'date', 'category' and 'class'. Then the missing information were removed, considering the amount of information, reducing from 31316 to 28846.

> Exploratory Data Analysis
>> The data evaluation presented that simple systemic antibiotic and antidepressant were the most registered considering the period from 1995 onwards. Being major from similar or generic category.

> Predictive Modeling
>> To forecast the information about new possible registers were performed DecisionTree method. Considering the data profile, the results presented suitable considering the metrics. Other methods, Random Forest and Support Vector Machine, didn't presented better results, the precision were considered for the evaluation.

>> The new profile consider the other categories, specific, phytotherapeutic, biological and dynamized, and the differences in the classes are presented in a WordCloud,



## Contribution Guidelines

Contributions are welcome! Please refer to the [Contribution Guidelines] for information on how to contribute to this project.

## Acknowledgements

ANVISA for the dataset.

## License

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](.LICENSE)
<hr>
<hr>

## Contact

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leandrodmf/)

![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)(leandrodemouraf@gmail.com)
## Disclaimer

This project is for research and educational purposes only. The findings should not be considered financial or investment advice.
