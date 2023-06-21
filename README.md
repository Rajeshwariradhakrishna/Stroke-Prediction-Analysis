

=======

**About the stroke:**

Stroke interrupts blood flow to an area of the brain. Strokes can be fatal, but the risk can be reduced. Many stroke risk factors are lifestyle related, so everyone has the power to reduce their risk of having a stroke. More than 80% of strokes can be prevented. If you have had a stroke, you are at high risk for another stroke. 1 in 4 stroke survivors has another stroke within 5 years. You are likely to experience some physical and neurological complications after a stroke. These complications may be minor or major, and the complications may be temporary or permanent depending on the size of the stroke and what part of the brain was affected.

**About the Dataset:**

ID - A unique identifier for the patient.

Gender - The gender of the patient (Male, Female, Other).

Age - The age of the patient.

Hypertension - Records if the patient has hypertension or not (0, 1).

Heart Disease - Records if the patient has a heart disease or not (0, 1).

Residence Type - What area the patient lives in (Rural, Urban).

Smoking status - Records the smoking status of patient (formerly smoked, never smoked, smokes, Unknown).

Stroke - Records if the patient has had a stroke or not (0, 1). This is the response variable we try to predict.

**Project Description:**

The objective of this project is to utilize stroke data to create a predictive model for identifying individuals who have a higher likelihood of experiencing a stroke. Our team will be analyzing the correlation and impact between risk factors and the occurrence of strokes in individuals. 

**Team Members:**

•	Aisha Henderson

•	Kelly Blake 

•	Rajeshwari Radharkrishna

•	Elona Barjami 


Research Questions:
1.	Does a person’s residency type increase the risk of having a stroke? Are individuals that live in Urban settings more likely to have a stroke vs. those that live in a Rural setting?
2.	Are males over 60 at a higher risk of having a stroke compared to males overall? Does smoking status (current smoker) have an impact on the likelihood of stroke for both populations?
3.	Are patients with hypertension vs patients with heart disease more likely to have a stroke?

**Task Distribution:**

• Kelly Blake - Research question 1, Data cleaning

• Aisha Henderson - Research question 2, Presentation

• Rajeshwari Radhakrishna - Research question 3, Github


**Research Question 1:** Does a person’s residency type increase the risk of having a stroke? Are individuals that live in Urban settings more likely to have a stroke vs. those that live in a Rural setting?
1. My analysis of this dataset resulted in a null hypothesis for residency type affecting the likelihood of stroke, which directly contradicted my further research. I also analyzed the percentages of each residency type and they were also very similar. The dataset documentation did not indicate when or where the sample was taken.
2. Overall I concluded the following: • There are striking and growing disparities in treatment for acute stroke in rural versus urban areas. Although rural residents are more likely to have a usual source of health care (“a place to which they usually go when they are sick”), they are still less likely to have a local hospital and physician, more likely to be uninsured, and tend to report fewer annual health care visits. Such disparities may have an impact on stroke incidence in rural and urban areas given that the availability of health care resources has a strong influence on risk factor prevalence, awareness, treatment, and control. • Stroke mortality is higher in rural compared with urban areas of the United States, and this seems to be because of higher stroke incidence rather than stroke case fatality. • Embolic strokes are caused by a blood clot or plaque debris that develops elsewhere in the body and then travels to one of the blood vessels in the brain through the bloodstream and occur more frequently in urban populations • Thrombotic strokes are caused by a blood clot that develops in the blood vessels inside the brain and are more prevalent in rural populations. Sources: https://www.hopkinsmedicine.org/health/conditions-and-diseases/stroke https://newsroom.heart.org/news/disparities-in-stroke-care-at-urban-vs-rural-hospitals-impacts-quality-of-care-patient-survival

**Question 1, Graphic 1**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/7e944b67-01bd-4f0e-a525-3a62deacc2bc)


**Research Question 2:** Is the rate of stroke higher in males who are older than 60 vs males between ages 20 - 59? For this combined population, does smoking status have an impact on the rate of stroke?

1. Part 1 of the analysis seeks to compare the risk of stroke, based on gender and age as factors.
The first visualization captures the rate of stroke for males over 60 years old. This indicates that 12.4% of males in this population had a stroke, versus 87.6% of males in this population who did not have a stroke.
The second visualization captures the rate of stroke for males between 20 - 59 years old. Findings indicate only 2.3% of males had a stroke, and 97.7% of males in this population group that did not have a stroke.
When combining the datasets to compare both age groups (60+ and 20 - 59), we can conclude based on the statistics that males over 60 years old are at a greater risk for stroke, with 4.4% having had a stroke. Males ages 20 - 59 years old who had a stroke is only 1.5%. When conducting an independent T-test, a statistic of 6.6 and a p-value of 5.6 indicate there is a correlation between age and the risk of stroke.

**Question 2, Graphic 1**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/cf1ddca7-5131-495f-9e7c-547bef6847c7)


**Question 2, Graphic 2**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/3330d805-96d3-4601-b743-99033f510987)

**Question 2, Graphic 3**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/e8c3f4a0-57ba-4cea-8be9-74688aba608f)


2. Part 2 of the analysis seeks to determine if there is a correlation between smoking status and an increased risk of stroke for males over 20 years old.
For part two of the analysis, only gender and smoking status are considered in determining the subset of the population from the dataset, looking at all males over the age of 20 to calculate the rate of stroke based on smoking status. There are a total of 855 male smokers and non-smokers in this population. Based on the data, there are 21 male smokers who had a stroke versus 25 male non-smokers who had a stroke.
When calculating the rate of stroke based on smoking status, it was determined that the rate of stroke for non-smokers is 3%, while the rate of stroke for smokers is 2%. The additional statistical analysis with an independent t-test was performed, producing a p-value of 0.160. Because this is greater than a p-value of 0.05, this indicates very low correlation between smoking status and the risk of stroke.

**Question 2, Graphic 4**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/1872780a-d167-46eb-8372-ce8eba5918b9)


**Research Question 3:** Are patients with hypertension vs patients with heart disease more likely to have a stroke?

1. Our dataset showed a higher percentage of the population had hypertension over heart disease. 

2. The percentage of people who have hypertesnion and had a stroke is higher than percentage of people who don't have hypertension who had a stroke. The percentage of people who have heart disease and had a stroke is higher than percentage of people who don't have heart disease who had a stroke.

3. It does not necessarily mean that people who has hypertension/heart disease will definetly have a stroke. There can be other factors which can cause a stroke in people. But there is high likely chance that people with hypertension and heart disease will be at the biggest risk of having a stroke.

4. Hypertesnion is the biggest risk factor for stroke. People with hypertension who got stroke is higher than people with heart disease who had stroke. People with hypertension had stroke is 62.8% and people with heart disease had a stroke is 37.2%.

**Question 3, Graphic 1**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/950f14a9-77e7-4280-8ece-8654bceedd8e)

**Question 3, Graphic 2**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/9fee54c1-786b-4a7b-9fb9-bdfc3741d18d)

**Question 3, Graphic 3**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/3da4e02a-9d07-475c-88af-75d586a59b4a)

**Question 3, Graphic 4**
![image](https://github.com/Rajeshwariradhakrishna/Stroke-Prediction-Analysis/assets/131278014/4e2e29a8-15a5-46f4-b538-932b8de67d79)


**Conclusion and Findings**
In conclusion, based on our analysis of the three research questions we found that:

1. There is no statistical significance in the rate of stroke for Urban vs Rural populations. The null hypothesis was proven to be true through analysis via Chi-Square testing and review of the p-value of these factors.
   
2. Males over the age of 60 have a higher risk of experiencing a stroke, over males ages 20 - 59 years of age. When looking at smoking status and the impact on stroke for the combined male population over 20, it was found that 3% of male non-smokers had a stroke, vs 2% of male smokers who had a stroke, indicating low correlation between smoking status and the risk of stroke.

3. Lastly, The percentage of people who have hypertesnion and had a stroke is higher than percentage of people who don't have hypertension who had a stroke. The percentage of people who have heart disease and had a stroke is higher than percentage of people who don't have heart disease who had a stroke.
   
**Data Limitations:**

The limitations of this dataset include a lack of information about where the sample population comes from (i.e, where they live, access to prevention and healthcare services, etc), as this information would prove useful in determining other contributing risks.
Additionally, other comorbidities that may have an impact on the rate of stroke are not available. While this question looks specifically at age and smoking status, it is clinically relevant to understand any other medical history, current diagnoses, and family history that may cause an increased risk of stroke outside of/or in addition to age and smoking status.
Lastly, additional information on the timeline and order of events regarding stroke vs diagnosis of available risk factors is not available, as well as how long the population has had a specific diagnosis.

**Dataset to Be Used:**

Description: The dataset below contains data for around 5000 unique stroke patients, with columns included for individual clinical diagnoses, and demographic information. 

[Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

Source: kaggle
main
