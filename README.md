# matplotlib-challenge

In this study, I will investigate and compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens used to target squamous cell carcinoma (SCC) tumors over the course of 45 days. I will use records pertaining to tumor development in a sample of 249 mice to generate tables and figures needed for the technical report of the clinical study, as well as a top-level summary of the study results.

In preparing the data I will:

- Display the  number of unique mice IDs

  <img width="1397" alt="Screenshot 2023-11-10 at 2 22 16 PM" src="https://github.com/anastasiaskr2000/matplotlib-challenge/assets/131491720/93eae35b-0e3f-4e9b-b019-7bd04c261780">

In generating summary statistics I will:

- Create a DataFrame of summary statistics for each drug regimen

  <img width="1402" alt="Screenshot 2023-11-10 at 2 23 39 PM" src="https://github.com/anastasiaskr2000/matplotlib-challenge/assets/131491720/848de5bb-f4a1-44e9-a53f-5992e527fd3e">

Create Bar Charts and Pie Charts: 

<img width="1385" alt="Screenshot 2023-11-10 at 2 24 58 PM" src="https://github.com/anastasiaskr2000/matplotlib-challenge/assets/131491720/6462113b-0e37-42b1-9748-89e336a5a2fd">

<img width="1406" alt="Screenshot 2023-11-10 at 2 25 27 PM" src="https://github.com/anastasiaskr2000/matplotlib-challenge/assets/131491720/c28d4edb-6420-4c4b-a853-9a59ac85d1bc">

Calculate Quartiles, Find Outliers, Create a Box Plot, a Line Plot and a Scatter Plot:

<img width="1370" alt="Screenshot 2023-11-10 at 2 26 12 PM" src="https://github.com/anastasiaskr2000/matplotlib-challenge/assets/131491720/f4bea511-f716-4faa-b0ac-966fbea47daa">

<img width="1376" alt="Screenshot 2023-11-10 at 2 26 37 PM" src="https://github.com/anastasiaskr2000/matplotlib-challenge/assets/131491720/6b2aacf2-1bf5-4679-9953-ea60ac6d5d28">

<img width="1367" alt="Screenshot 2023-11-10 at 2 27 02 PM" src="https://github.com/anastasiaskr2000/matplotlib-challenge/assets/131491720/02c9d152-0d8d-45d0-b6e5-b417ad8c34df">

Calculate Correlation and Regression:

<img width="1370" alt="Screenshot 2023-11-10 at 2 28 08 PM" src="https://github.com/anastasiaskr2000/matplotlib-challenge/assets/131491720/9a23b25f-8899-404e-b157-15a1332c13e6">

Conclusion: 

## Based on Summary Statistics, we can conclude that Capomulin and Ramicane are the most effective drug regimens for squamous cell carcinoma (SCC). The mean and median tutor volumes for Capomulin and Ramicane are the lowest when compared to the remainder of drug regimens tested on mice, indicating smaller tumor sizes in response to the abovementioned drug regimens. Their respective effectiveness is also proven by the tumor volume variance values for each drug, with Capomulin sitting second lowest with a 24.9 score and Ramicane sitting lowest with a 23.5 score, signifying a consistent tumor volume decrease rate. Considering that the number of mice on Capomulin and Ramicane is much higher than that of mice on other regiemns we can explain the lower tumor volume variance with the sample population size: the greater the number of specimen, the lower the variance. Considering the Weight vs Tumor Volume for Capomulin scatter plot, we can deduce that a crucial factor impacting tumor size is weight: the greater the weight, the larger the tumor. The relationship between weight and tumor volume is therefore proportional, as can be seen in the linear congregation of scatter points on the graph. Considering the impact that weight has on the regimen's ability to decrease tutor volume,  the mean/median values for Capomulin, as well as its clear and consistent ability to decrease tumor volume (see Capomulin Treatmeant of Mouse l509), it is the most consistently affective drug regimen for SCC. Since the sole outlier of the data is Infubinol, which also reports the highest tumor volume values (see Distrubution of Tumor Volume per Treatment Group), we can conclude that it is the most irregular and least consistent drug regimen to treat SCC. One of the limitations of this dataset is its lack of an equally thorough investigation of the effectiveness of Ramicane, which is a close competitor of Capomulin reporting close numbers as seen in the Summary Statistics section of the analysis. It would be beneficial to perform data analysis and visualizations to see how mice respond to it based on weight and tumor volume, since gender does not appear to have any notable impact on drug regiman effectiveness.   


