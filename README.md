# Project: Cement Strength Prediction

## Overview

In this project, the goal is to predict the compressive strength of concrete. This is a regression problem, where we aim to estimate the concrete's compressive strength (in MegaPascals - MPa) based on various input variables that describe the components and properties of the concrete mixture.

## Data Description

The dataset contains the following variables:

1. **Cement (component 1)**
   - Data Type: Quantitative
   - Measurement Unit: kg/m^3
   - Description: The amount of cement in a cubic meter of the concrete mixture.

2. **Blast Furnace Slag (component 2)**
   - Data Type: Quantitative
   - Measurement Unit: kg/m^3
   - Description: The amount of blast furnace slag in a cubic meter of the concrete mixture.

3. **Fly Ash (component 3)**
   - Data Type: Quantitative
   - Measurement Unit: kg/m^3
   - Description: The amount of fly ash in a cubic meter of the concrete mixture.

4. **Water (component 4)**
   - Data Type: Quantitative
   - Measurement Unit: kg/m^3
   - Description: The amount of water in a cubic meter of the concrete mixture.

5. **Superplasticizer (component 5)**
   - Data Type: Quantitative
   - Measurement Unit: kg/m^3
   - Description: The amount of superplasticizer in a cubic meter of the concrete mixture.

6. **Coarse Aggregate (component 6)**
   - Data Type: Quantitative
   - Measurement Unit: kg/m^3
   - Description: The amount of coarse aggregate in a cubic meter of the concrete mixture.

7. **Fine Aggregate (component 7)**
   - Data Type: Quantitative
   - Measurement Unit: kg/m^3
   - Description: The amount of fine aggregate in a cubic meter of the concrete mixture.

8. **Age**
   - Data Type: Quantitative
   - Measurement Unit: Days (ranging from 1 to 365)
   - Description: The age of the concrete in days when its compressive strength was measured.

9. **Concrete Compressive Strength**
   - Data Type: Quantitative
   - Measurement Unit: MPa (MegaPascals)
   - Description: The target variable we want to predict, which represents the compressive strength of the concrete.

## Objective

The objective of this project is to build a machine learning model that can accurately predict the compressive strength of concrete based on the input variables listed above. Various regression techniques and models will be explored to achieve this goal.

## Data Source

The dataset used for this project is provided here : https://github.com/mrvinayakjha/project-cement-strength-prediction/blob/main/cement_data.csv
