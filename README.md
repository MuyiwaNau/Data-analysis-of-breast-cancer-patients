# Data-analysis-of-breast-cancer-patients

Breast cancer is the most common cancer in women around the world. In 2020 alone, there were **2.3 million women diagnosed** with breast cancer and **685,000 deaths** globally. As of the end of **2020**, there were **7.8 million women alive who were diagnosed with breast cancer** in the past five years, making it the world’s most prevalent cancer. In addition, around **0.5-1% of cancer patients are male**.

Breast cancer arises in the lining cells (epithelium) of the ducts (85%) or lobules (15%) in the glandular tissue of the breast. Initially, the cancerous growth is confined to the duct or lobule (“in situ”), where it generally causes no symptoms and has minimal potential for spread (metastasis). 


# **Table of contents:**
- **Patient_ID**: Unique identifier for each patient.
- **Age**: Age of the patient.
- **Gender**: Gender of the patient.
- **Protein1**: Data related to Protein 1.
- **Protein2**: Data related to Protein 2.
- **Protein3**: Data related to Protein 3.
- **Protein4**: Data related to Protein 4.
- **Tumour_Stage**: Stage of the tumor.
- **Histology**: Type of histology.
- **ER status**: Estrogen Receptor status.
- **PR status**: Progesterone Receptor status.
- **HER2 status**: HER2 status.
- **Surgery_type**: Type of surgery.
- **Date_of_Surgery**: Date of the surgery.
- **Date_of_Last_Visit**: Date of the patient's last visit.
- **Patient_Status**: Status of the patient.


## Resources
- **BreasCancer.csv**
- **Python**
  

## Findings

![image](https://github.com/MuyiwaNau/Data-analysis-of-breast-cancer-patients/assets/34709932/4aa8a975-fc63-4dd2-a720-cd8fea4bf7fb)

So now we see that in our dataset, 70.66% of cases are of the Infiltrating Ductal Carcinoma type, 25.55% are of the Infiltrating Lobular Carcinoma type, and only 3.79% are of the Mucinous Carcinoma type. This fits with the fact that Infiltrating Ductal Carcinoma is the most common type of breast cancer; in any given sample dataset, it likely is the most popular of all the types.


![image](https://github.com/MuyiwaNau/Data-analysis-of-breast-cancer-patients/assets/34709932/6d2aeb39-5cf2-4a9f-86b8-d4b804c65f75)

So now we see that in our dataset, 70.66% of cases are of the Infiltrating Ductal Carcinoma type, 25.55% are of the Infiltrating Lobular Carcinoma type, and only 3.79% are of the Mucinous Carcinoma type. This fits with the fact that Infiltrating Ductal Carcinoma is the most common type of breast cancer; in any given sample dataset, it is likely that it is the most popular of all the types.


![image](https://github.com/MuyiwaNau/Data-analysis-of-breast-cancer-patients/assets/34709932/17070785-610f-47fb-9984-1d794667c6ce)

From the above chart, we can see that deaths in all age ranges follow a normal distribution, the same as the overall distribution of the number of cases. We could try to get the percentages for each age range, but considering that we have an uneven number of patients, our results could be deciphered incorrectly.



## Conclusions
We started this analysis to see any trends or correlations between the different attributes in breast cancer patients. After our analysis, we see the following trends:

- Male cancer patients make up a little more than 1% of all breast cancer patients in the dataset.
- Approximately 40% of patients with breast cancer are in the age range of 40-65.
- The majority of patients with breast cancer have the Infiltrating Ductal variety.
- Number of dead vs live patients by age range
- Mortality rate by cancer type
  

## Future Analyses
In keeping with the findings of this analysis, I would like to research further on male patients, Stages of Cancer, and protein markers.
