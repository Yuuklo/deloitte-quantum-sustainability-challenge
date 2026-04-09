# Deloitte Quantum Sustainability Challenge 2026
by Jaewon Park, Calvin Wang, Erik Vo | parkjaew@bc.edu, wangcalv@bc.edu, voer@bc.edu  

  
**Challenge Description**
> The Competition aims to explore the potential for quantum computing—specifically machine learning algorithms—to enhance wildfire risk prediction and improve insurance premium modeling for urban areas in California facing growing wildfire risks. As the unpredictability and severity of wildfires rises, societies across the globe need to increasingly adapt to the profound financial impacts of these events on local and regional economies.

**Tasks**
> Task 1A: Create a quantum algorithm, a (hybrid) quantum machine learning model, that predicts the future risk of a wildfire occurring in California zip-codes in 2023, based on historical data (2018-2022) which are provided in the wildfire dataset. To reduce complexity, a ‘wildfire’ will be defined by if it burns in a wildland setting and is unplanned and uncontrolled. Run your algorithm on a quantum computer or simulator and provide information on the resource requirements of your solution.

> Task 1B: Evaluate your solution, describing the advantages and disadvantages of your approach(es). Evaluate the performance differences between your solution and classical approaches.

> Task 2: Create a time series model to predict future insurance premiums in 2021 based on historical data (2018-2020) provided in the insurance dataset. Wildfire risk for each zip code is provided by the model output in Task 1 or use the existing fire risk score provided in the dataset.

**Contents**

This repository contains the following folders:

- `data`
- `notebooks`
- `reports`
---
Libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`  
Services: `AWS Braket`, `IBM Quantum`
