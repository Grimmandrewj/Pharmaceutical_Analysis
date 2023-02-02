## Goal
- I was tasked with analyzing two datasets to evaluate the effectiveness of several drug regimens on 249 mice who were identified with SCC tumors.  
- The assignment identified Capomulin as the drug of interest and tasks me with measuring against the other regimens' success.  
- I was to generate all the tables and figures needed to support the clinical study and facilitate in evaluation of the drug's effectiveness

## Method
- I analyzed both datasets and created DataFrames that organized the data by Mouse ID, summary statistics (such as mean, median, variance, standard deviation, and SEM of the tumor volume in the mice).  
- Duplicate mouse data was also identified and dropped from the dataset
- Bar charts were generated to show the total amount of mice tested per regimen
- Pie charts were generated to show the percentage of male vs. female mice
- The quartiles of final tumor volumes and outliers were calculated and charted in a box plot, and jthe average tumor volume by weight was demonstrated on a scatter plot, on which the correlation between the data was finally calculated

## Results
- Capomulin was shown to be the most effective drug regimen with similar results to a competing regimen: Ramicane: 

![image](https://user-images.githubusercontent.com/120341249/216242995-af3c1d73-8315-47df-a95e-8382a29bf524.png)

- One outlier was identified in the group of mice treated with Infubinol, suggesting the data from the study is consistent

- The correlation between mouse weight and final tumor volume was also demonstrated as well: 

![image](https://user-images.githubusercontent.com/120341249/216243173-f02f36c7-88d2-4d22-9992-255981bcacd4.png)


