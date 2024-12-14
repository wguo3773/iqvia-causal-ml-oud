# iqvia-causal-ml-oud
Modeling the risk of treatment discontinuation in MOUD - Subgroup analysis of disparities using Causal Machine Learning  

Background: 
Opioid use disorder (OUD) poses a public health crisis in the US. Despite the effectiveness of Buprenorphine in treating OUD, treatment discontinuation remains a critical challenge. 

Motivation: 
Current strategies to predict Buprenorphine treatment discontinuation often fail to capture the heterogeneity in treatment responses across diverse populations, leading to less effective interventions.

Implementing a two-stage virtual twins model allows for the identification of subgroups particularly vulnerable to disparities in discontinuation, enabling tailored interventions to improve treatment retention.

![image](https://github.com/user-attachments/assets/89c45d18-f6a2-4880-b2e8-9153db0771f4)


Significance and Conclusion  
1. Our study is the first to use Nationwide, longitudinal, and treatment Episode-level data in ML models instead of prescription data, enabling better capture of Tx outcomes. 
2. We Identified Key Subgroups with disparities that traditional approaches could not achieve, increasing tailored strategies and policy to improve retention 
3. We found protective effects for health services predictors related to improving adherence (mental health, counseling, psychotherapy, induction and maintenance Tx) previously not reported in literature. 
4. By innovatively integrating with SDOH, we found strong community-level Socioeconomical gradient with probability of retention using SVI, buprenorphine provider and mental health provider density – a key novelty in this study. 
5. This would tremendously improve Policy decision making and/or targeted treatment strategies to overcome the opioid crisis


Here are the links to the files - <br> 
Slides - https://github.com/wguo3773/wguo3773.github.io/blob/main/assets/publications/Wnaru%20Guo%20HACASA%202025%20copy.pptx <br> 
Poster - 

Code (R Markdown): <br> 
1. Data Pre-processing - https://github.com/wguo3773/iqvia-causal-ml-oud/blob/main/AIM-AHEAD%20Project%2000%20Data%20Processing%20WG_CB%20updated.html 
2. Exploratory Data Analysis - https://github.com/wguo3773/iqvia-causal-ml-oud/blob/main/AIM-AHEAD%2002%20EDA%20CB_WG%20updated.nb.html
3. Identifying Buprenorphine treatment episodes - https://github.com/wguo3773/iqvia-causal-ml-oud/blob/main/AIM-AHEAD%20-%20Tx_Episodes_Analysis%20.html
4. Cox Proportional Hazards Model for modelling treatment discontinuation - https://github.com/wguo3773/iqvia-causal-ml-oud/blob/main/AIM-AHEAD%20-%20Cox_PH.html 
5. Virtual Twins ML subgroup Analysis for treatment discontinuation - https://github.com/wguo3773/iqvia-causal-ml-oud/blob/main/AIM%20AHEAD%20Virtual%20Twins%20WG.html










