# Predicting Energy Usage in Buildings



![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)

### Problem Description
The primary objective of this project is to develop a robust model capable of accurately predicting energy consumption in buildings. This endeavor involves harnessing historical energy usage data in conjunction with diverse weather and environmental variables to construct an effective predictive model. By achieving precise energy consumption forecasts, both building proprietors and energy providers stand to benefit from enhanced energy management, the identification of energy-conserving prospects, and the ability to make well-informed decisions geared toward diminishing energy expenditures and ecological footprint.

## Project Structure

The project repository is organized as follows:

```

├── LICENSE
├── README.md           <- README .
├── notebooks           <- Folder containing the final reports/results of this project.
│   │
│   └── energy_usage.py   <- Final notebook for the project.
├── reports            <- Folder containing the final reports/results of this project.
│   │
│   └── Report.pdf     <- Final analysis report in PDF.
│   
├── src                <- Source for this project.
│   │
│   └── data           <- Datasets used and collected for this project.
|   └── model          <- Model.

```

### Dataset Information
The project relies on the utilization of the "KAG_energydata_complete" dataset, which encompasses historical records of energy usage within a building. This dataset encompasses an array of sensor readings, weather information, and corresponding energy consumption measurements collected over a span of time. The dataset is comprised of the following columns:

- Temperature (T1-T9): Temperature readings from distinct locations within the building.
- Humidity (RH_1-RH_9): Humidity measurements from various points inside the building.
- Weather Variables: External factors including outdoor temperature (T_out), dew point temperature (Tdewpoint), outdoor humidity (RH_out), atmospheric pressure (Press_mm_hg), windspeed, and visibility.
- Light: Intensity of light recorded within the building.
- Random Variables: Two arbitrary variables (rv1 and rv2) devoid of specific significance.
- Appliances: Energy consumption attributed to the building's appliances (the target variable).

### Background Information
Efficient energy utilization within buildings is a pivotal facet of sustainable energy management. In light of the escalating emphasis on energy efficacy and ecological sustainability, the accurate prediction of energy consumption takes on paramount importance. Through the analysis of historical data combined with external influencers such as weather conditions, building proprietors can optimize energy usage, curtail costs, and enhance overall energy efficiency.

The dataset offers an extensive array of variables that have the potential to exert an impact on energy consumption. By scrutinizing the interrelationships between these variables and the target variable (appliance energy consumption), we can construct a predictive model capable of projecting energy usage grounded in prevailing and anticipated weather conditions, temperature fluctuations, and additional pertinent factors.

### Project Overview
This undertaking encompasses several pivotal stages:

1. Data Exploration and Visualization: The initial phase involves delving into the dataset, comprehending its structure, and visualizing the distribution of variables. This helps identify patterns and outliers, which in turn informs subsequent steps.

2. Data Preprocessing: This phase entails cleaning the data, handling missing values, and potentially normalizing or scaling certain features to prepare them for model training.

3. Model Implementation: A range of regression algorithms, including Ridge regression, Lasso regression, Support Vector Regression, K-Nearest Neighbors Regressor, Random Forest Regressor, Gradient Boosting Regressor, Extra Trees Regressor, XGBoost Regressor, and Multi-Layer Perceptron Regressor, are evaluated. The goal is to ascertain the most adept model for energy consumption prediction.

4. Model Evaluation: The effectiveness of each model is gauged using metrics such as the R2 score and root mean squared error (RMSE). These metrics provide insight into the accuracy and precision of the models' predictions.

### Conclusion
Through the accurate prediction of energy consumption in buildings, this project endeavors to furnish actionable insights and recommendations aimed at optimizing energy management, promoting energy efficiency, and curtailing environmental impact. The synthesis of historical data and pertinent variables empowers stakeholders to make informed decisions, thereby advancing the cause of sustainable energy utilization.

## License

This project is licensed under the [MIT License](LICENSE).
## Author
- <ins><b>©2023 Tushar Aggarwal. All rights reserved</b></ins>
- <b>[LinkedIn](https://www.linkedin.com/in/tusharaggarwalinseec/)</b>
- <b>[Medium](https://medium.com/@tushar_aggarwal)</b> 
- <b>[Tushar-Aggarwal.com](https://www.tushar-aggarwal.com/)</b>
- <b>[New Kaggle](https://www.kaggle.com/tagg27)</b> 

## Contact me!
If you have any questions, suggestions, or just want to say hello, you can reach out to us at [Tushar Aggarwal](mailto:info@tushar-aggarwal.com). We would love to hear from you!