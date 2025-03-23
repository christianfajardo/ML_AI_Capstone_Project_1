# UC Berkeley | Professional Certificate in Machine Learning and Artificial Intelligence
## Capstone Project 1 (Module 20)

**Author**: 

Christian Fajardo
___

##### Note: Due to inaccessiblity of data sources originally defined in Module 17, I needed to identify and select an alternative that is closely related to the manufacturing industry.

---

### Executive summary
#### Rationale

Why should anyone care about this question?

Preventive maintenance is critical in modern manufacturing to minimize unplanned downtime, reduce costs, and extend equipment lifespan. Using predictive machine learning (ML), manufacturers can anticipate failures before they occur by analyzing patterns in real-time operational data. 

This proactive approach enables timely interventions that avoid costly breakdowns and production delays. ML-driven maintenance also improves resource allocation by focusing efforts where they are needed most, rather than relying on fixed schedules. 

As a result, companies can significantly increase operational efficiency and asset reliability. Investing in predictive maintenance using ML is a strategic move that drives long-term savings and strengthens competitive advantage.
___

### Research Question
Will a manufacturing machine or product experience a failure that could disrupt production operations?

___

### Data Sources
Data source: https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification
___

### Methodology
What methods are you using to answer the question?

For this dataset my methodology may include training supervised machine learning models such as K-Nearest Neighbors (KNN), Decision Trees, Logistic Regression, and Support Vector Machines (SVM) to predict potential machine failures. 

___

### Results
The initial dataset intended for this research was not feasible to acquire due to access limitations. As a result, I pivoted to an alternative dataset that remains highly relevant to the manufacturing industry, aligning with my professional domain. 

The new dataset, sourced from Kaggle, is titled "Machine Predictive Maintenance Classification" and focuses on forecasting equipment failures using sensor data. It contains 10,000 rows and 14 columns, offering a rich set of features including temperature, rotational speed, torque, and tool wear.

These variables are directly applicable to real-world manufacturing operations, making the dataset suitable for predictive maintenance modeling. 
This shift ensures that the research remains grounded in practical industry applications while maintaining analytical rigor.

**Results**

Based on the initial analysis, data shows the correlation table shows a strong positive correlation between `Air Temperature` and `Process Temperature` (r = `0.88`), indicating they increase together. 

Rotational speed `RPM` and `Torque` have a strong negative correlation (r = -0.88), suggesting that higher speed is associated with lower torque. Failure has the highest positive correlation with torque (r = `0.19`) and tool wear (r = `0.11`), though these correlations are still relatively weak. 

Overall, most variables show low direct correlation with failure, implying other factors or combinations may be at play.
___

### Next steps
What suggestions do you have for next steps?
___

### Outline of project

- `README.md`: Documentation.
- `data/`: Contains the cleaned dataset used for analysis.
- `images/`: Contains plot images.



##### Contact and Further Information