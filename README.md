# UK-Road-Traffic-Accident-Analysis

**Introduction:**  
Accidents occur due to various factors, and understanding these factors can aid in predicting their likelihood and mitigating their consequences. This project leverages real-world data from UK road traffic accident reports in 2020 to provide insights into accident patterns and outcomes. By employing data-driven approaches, the aim is to suggest strategies for enhancing road safety and minimizing risks associated with accidents.

**Objectives:**

- Investigate if there are specific hours of the day and days of the week when accidents occur more frequently.
- Analyze accident patterns for different categories of motorcycles, including Motorcycle 125cc and under, Motorcycle over 125cc and up to 500cc, and Motorcycle over 500cc.
- Examine the hours of the day and days of the week when pedestrians are more likely to be involved in accidents.
- Utilize the Apriori algorithm to explore the impact of selected variables on accident severity.
- Identify and analyze accidents within specific regions, such as Kingston upon Hull, Humberside, and the East Riding of Yorkshire, through clustering techniques.
- Implement outlier detection methods to identify unusual entries in the dataset and assess their relevance for analysis.
- Develop a classification model using the provided data to accurately predict fatal injuries sustained in road traffic accidents, aiming to inform and improve road safety measures.


**Methodology:**  
The methodology involves data preprocessing, association mining, clustering, and predictive modeling. Techniques such as the Apriori algorithm and Random Forest, decision tree, and Gradient Boost algorithms are utilized to understand accident causes, predict accident severity, and derive actionable insights.

**Data Description and Cleaning:**  
The dataset comprises multiple tables, including accident, vehicle, casualty, and LSOA of the accident location. Data cleaning involves addressing missing values, negative entries, and inconsistencies. Techniques such as replacing missing values and normalizing data are employed to ensure the dataset's integrity and reliability.

**Accident Demography:**  
Geographical analysis reveals accident hotspots in major urban cities such as London , Manchester Liverpool, Leeds, and Birmingham. Most accidents occur on single-carriage roads within urban areas, with the majority categorized as minor. Analysis of casualty and driver demographics highlights trends in age groups and gender distribution.

![hotspot](https://github.com/adewoleaj/UK-Road-Traffic-Accident-Analysis/blob/main/accodemt%20decom%20.png?raw=true)

                                UK Accident Hotspot

**Data Insights:**  
Insights are drawn regarding the significant hours and days of the week for accidents occurrence, with spikes observed during rush hours and on Fridays. Motorcycle accidents also exhibit temporal patterns, with certain types of motorcycles and days of the week showing higher accident occurrences.

![weekly](https://github.com/adewoleaj/UK-Road-Traffic-Accident-Analysis/blob/main/data%20insgint%20.png?raw=true)

            Distribution of accident occurrence per weekdays for different casualty types

**Effect of Light and Weather Conditions:**  
Analysis indicates that the majority of accidents occur during daylight and fine weather conditions. Adverse weather conditions have minimal impact on accident occurrence, potentially reducing accidents due to decreased driving activity.

![weather](https://github.com/adewoleaj/UK-Road-Traffic-Accident-Analysis/blob/main/weather%20condition%20.png?raw=true)

                      Effect of light and weather conditions on accident

**Prediction:**  
Predictive models, particularly Random Forest, demonstrate strong performance in predicting accident severity, with commendable recall rates and accuracy. Cross-validation enhances model metrics, highlighting the model's robustness in identifying fatal accidents.

![predictive model](https://github.com/adewoleaj/UK-Road-Traffic-Accident-Analysis/blob/main/predictive%20model%20.png?raw=true)

Model performance metric of different classification algorithm and Random Forest classification report and confusion matric 

**Recommendations:**

Based on the analysis, the following recommendations are proposed:
1. Optimize Urban Roads: Expand busy roads during rush hours or convert to dual carriageways for safer travel.
2. Promote Safer Motorcycles: Introduce policies to replace certain motorcycle types with safer electric ones.
3. Enforce Scooter Rules: Implement strict mobility scooter rules and speed limits in walkways.
4. Strengthen Friday Traffic Control: Increase traffic officer presence on Fridays to enhance road safety.


**Conclusion:**  
In conclusion, the project offers valuable insights and recommendations derived from comprehensive data analysis and predictive modeling. By leveraging data-driven approaches, it provides a framework for informing decision-making and implementing measures to improve road safety.

**Reference:**  
References to academic sources and relevant literature are provided for further exploration and validation of the project's findings.

**Usage:**
- Researchers and policymakers interested in road safety can utilize the insights and recommendations to inform decision-making and policy development.
- Data scientists and analysts can explore the methodologies and models implemented in this project for similar analyses in different contexts.
- Developers and stakeholders involved in road infrastructure and transportation planning can leverage the findings to prioritize safety measures and intervention

To run the script:

   1. Clone this repository.
   2. Ensure you have the required packages installed (**pandas**, **numpy**, **seaborn**, **matplotlib**).
   3. No additional configuration is required beyond the installation steps. However, you may need to adjust the path to your dataset and model directory according to your local setup
   4. Run the Python script housing_price_prediction.py


**Contributions:**
Contributions and feedback are welcome for further refinement and enhancement of the project.

**Note:**  
For detailed analysis and findings, refer to the project documentation, including the Jupyter notebook and report available in the repository(I used colab). 


## Author

**_Adewole Adetoro Ajala_**

For any inquiries, please contact: woltoaj@gmail.com / woltoajai@gmail.com / a.ajala-2021@hull.ac.uk

Feel free to contribute or provide feedback!

