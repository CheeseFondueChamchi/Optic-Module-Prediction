-Optical Module Lifecycle Prediction for 5G Base Stations

This project is designed to predict the lifecycle of optical modules deployed in 5G base stations. 
Optical modules are critical components typically installed in locations such as building rooftops, apartment complexes, and other distributed infrastructure.

-Problem Statement

One of the primary challenges of this solution is the sheer scale of deployment. 
The number of optical modules is as vast as the number of 5G base stations visible in a modern city. 
Moreover, the diversity of optical modules further complicates this problem, as various types and models are used across deployments.

-Data and Insights

Original Optical Power Data
The raw optical power data is the basis of our analysis, showcasing time-series characteristics that vary by module and environmental conditions.
![DU_RX_full](https://github.com/user-attachments/assets/e49897fb-2345-4477-94df-b71dc25eca38)


-Clue for Predictive Modeling

Despite the variability in power signals, certain standardized time-series patterns have been identified, 
which serve as clues for lifecycle prediction. 
These patterns enable the classification and subsequent lifecycle estimation.
![newplot](https://github.com/user-attachments/assets/9b85e282-3eb0-4264-b2db-c14219cf1e50)

-Solution Approach

Time-Series Pattern Classification:
Develop a classification model to identify and categorize the distinct patterns observed in optical power signals.

Model Optimization:
Explore and fine-tune hyperparameters for ensemble models and other advanced machine learning techniques to enhance prediction accuracy.
Lifecycle Prediction:

Predict the end-of-life (EOL) for each module. 
If no imminent failure is detected, the model concludes that the module is expected to operate continuously under current conditions.
Example Prediction Result

-Example Prediction Result

Below is an example of the prediction result, where the model determines the expected failure timeline for an optical module.
<img width="288" alt="image" src="https://github.com/user-attachments/assets/d7e4afba-de4c-4b62-a4da-85b9b56eb773">


Key Features
Scalable Deployment: Designed to handle massive datasets corresponding to large-scale 5G deployments.
Pattern Recognition: Leverages temporal patterns to enable accurate predictions.
Operational Insights: Provides actionable insights for proactive maintenance, reducing downtime.
