---
layout: archive
title: "Research Experiences"

author_profile: true

redirect_from: 
  - /research/
  - /research.html
---
Over the past few years, I’ve had the opportunity to work on several research projects that span statistics, cognitive science, and global health. These experiences have strengthened my skills in data wrangling, statistical modeling, and interdisciplinary collaboration — and deepened my curiosity for using data to answer real-world questions.

I’m currently working with Professor Emily Briceno at the University of Michigan, where our team focuses on cognitive aging, mild cognitive impairment (MCI), and cross-cultural neuropsychological assessment, particularly in low- and middle-income countries. My role includes data cleaning, variable harmonization, modeling cognitive outcomes, and navigating the complexities of large, multi-country studies.

More details on past and current projects are listed below. Stay tuned — I’m always exploring new directions.

---
## 🇳🇵 Nepal Cognitive Aging & MCI Assessment  
(with [Prof. Emily Briceno](https://experts.umich.edu/4331-emily-briceno) and [Prof. Dirgha Jibi Ghimire](https://psc.isr.umich.edu/profile/ghimire-dirgha-jibi/))

**Overview:** 
This project focuses on the **adaptation of neuropsychological assessments** for **low-literacy populations** in Nepal. Specifically, we aim to culturally and linguistically adapt two cognitive tests: a **visuospatial construction and visual memory task (Constructional Praxis)** and the **Symbol Cancellation test**, ensuring accessibility, validity, and reliability in underserved settings.

**My Contributions:**  
- Led the adaptation and scoring strategy refinement for Constructional Praxis and Symbol Cancellation tasks based on field protocols and response characteristics  
- Cleaned and harmonized raw test data from interviewer-administered paper forms and digital entry  
- Developed logic rules for identifying **“not assessed” vs. true 0 scores** under conditions of illiteracy or visual/motor limitation  
- Coordinated data integration with HCAP frameworks and harmonized Nepal-specific codebooks with U.S. and Mexico counterparts  
- Built reproducible R scripts for tracking missingness, scoring distributions, and variable creation across subtests

**Skills/Tools:** R, neuropsychological test coding, missing data management, HCAP harmonization, cross-cultural measurement  

---

## 🧠 HRS-HCAP Mild Cognitive Impairment Modeling  
(with [Prof. Emily Briceno](https://experts.umich.edu/4331-emily-briceno), [Prof. Zachary J Kunicki](https://vivo.brown.edu/display/zkunicki) and [Prof. Miguel Arce Rentería](https://www.neurology.columbia.edu/profile/miguel-arce-renteria-phd) )

**Overview:**  
Using data from the **U.S. Health and Retirement Study (HRS-HCAP)**, this project investigates **risk factors and diagnostic pathways** for mild cognitive impairment (MCI) among older adults. We analyze associations between demographic, medical, and psychological factors and MCI subtypes (with and without memory impairment).

**My Contributions:**  
- Conducted **data cleaning and integration** from HRS core files and HCAP cognitive batteries, with attention to longitudinal structure and variable alignment  
- Created derived variables (e.g., MCI subtype classification, CESD-based depression status, combined race/ethnicity categories)  
- Fit and interpreted **multinomial logistic regression models** to predict cognitive status across three groups: Normal, MCI w/ memory impairment, MCI w/o memory impairment  
- Generated **publication-ready summary tables and plots**, including stacked bar charts and model coefficient visualizations  

**Skills/Tools:** R (dplyr, ggplot2, nnet), multinomial logistic regression, variable engineering, large-scale survey data handling, reproducible reporting  


## 🐁 Digital Cages Behavioral Data Analysis (with [Prof. Ivo D. Dinov](https://nursing.umich.edu/faculty-staff/faculty/ivo-d-dinov) and Dr. [Simeone Marino](https://medschool.umich.edu/profile/2984/simeone-marino) ) 

**Overview:**  
This project explores high-resolution **actigraphy data** collected from mice housed in “digital cages” — an automated platform that passively captures movement-based behavioral patterns. Our aim is to identify **distinct activity profiles** and uncover **latent behavioral states** under varying experimental conditions.

**My Contributions:**  
- Cleaned and preprocessed large-scale time-series datasets, including timestamp alignment, sensor noise filtering, and missing value imputation  
- Applied **dimensionality reduction** (PCA, UMAP, t-SNE) to visualize behavioral trajectories across individuals  
- Performed **unsupervised clustering** (k-means, hierarchical) to identify natural groupings in activity patterns  
- Integrated **feature selection pipelines** using the NExOS algorithm for downstream supervised learning and behavioral prediction  

**Skills/Tools:** R, Python, data wrangling, PCA/UMAP, clustering, time-series analysis, scientific visualization  


## 🅿️ Algorithmic and Graph-Theoretic Analysis of Parking Functions  
**Advisor:** [Dr. Thomas Selig](https://scholar.xjtlu.edu.cn/en/persons/ThomasSelig)  
**Institution:** Xi’an Jiaotong-Liverpool University  
**Date:** Jun. 2024 – Aug. 2024

**Overview:**  
This project explores the **combinatorial and graph-theoretic structures underlying parking functions**, a classic object in enumerative combinatorics. Using tools such as **bipartite matchings**, **adjacency matrices**, and **friendship graphs**, we analyzed recurrence relations and structural properties of parking function families.

**My Contributions:**  
- Applied graph-theoretic methods to characterize and classify parking functions  
- Developed a simulation framework in **Python** using `NetworkX` and `NumPy`, enabling large-scale testing and model validation  
- Proposed novel multi-agent parking algorithms with **~40% improvement** in computational efficiency over standard methods  
- Conducted over **100,000 simulation trials** and visualized patterns using `Matplotlib`  
- Co-authored a manuscript in preparation, formalizing connections between parking functions and graph-based optimization  

**Skills/Tools:** Python, NetworkX, NumPy, Matplotlib, graph theory, combinatorics, algorithm design

**Poster Presentation:**  
🗓️ *Presented at the 2023 Summer Undergraduate Research Fellowships (SURF), Xi’an Jiaotong-Liverpool University*  
[![New Variations of Parking Function](images/SURF-2023-0167.jpg)](images/SURF-2023-0167.jpg)  
*Click the image to view the full poster.*


---

## 🔁 MVP Parking Functions in Abelian Sandpile Models  
**Advisor:** [Dr. Thomas Selig](https://scholar.xjtlu.edu.cn/en/persons/ThomasSelig)  
**Date:** Sept. 2023 – Jul. 2024  

**Overview:**  
This project investigates the **interplay between MVP parking functions and Abelian Sandpile Models (ASM)**, focusing on their application to self-organized criticality and resource allocation in discrete dynamical systems. Emphasis was placed on defining recurrence rules, modeling dynamic transitions, and testing feasibility through simulation.

**My Contributions:**  
- Conducted an in-depth **literature review** on MVP parking functions and their role in ASM and SOC systems  
- Extended the Abelian Sandpile Model to include parking function constraints and novel transition rules  
- Implemented Java-based simulations to study system stability, critical states, and recurrent configurations  
- Evaluated outcomes through **statistical and algebraic analyses**, validating theoretical expectations

**Skills/Tools:** Java, combinatorics, discrete dynamical systems, Abelian Sandpile Models, MVP parking functions  



**Talks and Posters:**

1. 2022 Summer@ICERM Final Presentation ([slide](https://app.icerm.brown.edu/assets/372/4320/4320_3425_Reutercrona-Wang-Whidden_080320221100_Slides.pdf))
2. 2023 Joint Mathematics Meeting - Pi Mu Epsilon Poster Session ([poster](files/pf_poster.pdf))
3. 2023 Joint Mathematics Meeting - Pi Mu Epsilon Contributed Session on Research by Undergraduates

## Determination of Average Time that A Particle Escapes from a Channel with Diverse Parameters

**Abstract:** As a particle bounces within a macroscopic billiard table, microstructures affect the frequency of output angles. There also exists a connection between macrostructures and microstructures, both of which determining particle behavior, which we quantify as the mean escape time. In the case of a microstructure that introduces specular diffuse collision law, the mean escape time is reminiscent of martingales and optional stopping theorem. With triangular microgeometry, the output angles are finite. We begin to construct the transition matrix which models the behavior of these output angles, and define the ways in which the angles transform within the triangular cells.

This research was completed at Summer 2021 REU at Mount Holyoke College with Ruozhen Gong and Emily Rosaci, under the mentorship of [Professor Timothy Chumley](https://tchumley.mtholyoke.edu/?_ga=2.98059675.564660943.1704846727-1838912408.1704846727). Our group wrote a [final report](https://tchumley.mtholyoke.edu/pdf/Summer_2021_research_report.pdf) and built an [R-shiny app](https://olypys-yuxuan-wang.shinyapps.io/Billiards_Probability_and_their_Interplay/) to showcase our results.

## Leveraging Financial News Analysis to Predict Stock Price Movement

**Abstract:** Stock market predictions have been prominent among scholars. Sentiment analysis applying financial news articles for predicting stock has also grown in popularity over the past few decades. Our research indicates the impact of sentiment analysis of financial news on forecasting asset prices. In this research, sentiment is culled from financial news of companies over the past three years. Subsequently the asset prices can be predicted using stock market data, alongside sentiment analysis data with several machine learning algorithms. The results show a more convincing level of precision in the aggregation of both stock market data and sentiment analysis data.

This research was completed in Summer 2020 CIS REU with Mingchen Xu (Shanghai International Studies University), Yiran Huang (Nankai University), and Mulei Xu, under the mentorship of Professor Patrick Houlihan at Columbia University. Our published paper is available [here](https://www.airitilibrary.com/Article/Detail/P20200813001-202107-202107160001-202107160001-265-276). 
