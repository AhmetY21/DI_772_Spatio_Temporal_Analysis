# :earth_americas: Global Fishing Data Analysis Study

## :mortar_board: DI 772 Final Project

This repository contains the data, notebooks, models, and analysis outputs for the "Global Fishing Data Analysis Study" conducted as part of the DI 772 course. The project focuses on spatial analysis of global fishing activities using various machine learning models and spatial autocorrelation techniques. 

This project was developed by Erdal Bozan and Ahmet Yüksel.

### :file_folder: Project Structure

This repository is organized into several directories, each designed to serve a specific purpose in the analysis workflow:

- **/data**: :bar_chart: Contains all datasets used in the analysis. These include data aggregated by different fishing methods such as trawlers, purse seines, and longlines.

- **/models**: :robot: Stores the serialized machine learning models that were trained as part of this analysis, including models like Decision Tree, Random Forest, Logistic Regression, Naive Bayes, and Ridge Classifier.

- **/output**: :chart_with_upwards_trend: Includes output files from the analysis, such as feature importance graphics and model evaluation metrics.

- **/notebooks**: :notebook: Jupyter notebooks with detailed data analysis, model building, and evaluation steps. Key notebooks include:
  - `fishing_data_modelling_v1.ipynb`: Main analysis notebook with model training and evaluation.
  - `fishing_data_analysis.ipynb`: Contains exploratory data analysis and initial findings.

- **kepler_map_predictions_hex_level_and_model_based.html**: :world_map: An interactive Kepler.gl map visualization that highlights model predictions at the hexagon level.

### :mag: Analysis Highlights

- **Data Analysis**: :fish: Analysed the different shipping data from different ships. Observed the seasonal and temporal changes of fishing ships.

- **Feature Importance Analysis**: :key: Evaluated the importance of various features for different fishing techniques using machine learning models.

- **Model Performance**: :trophy: Developed and assessed several machine learning models to predict fishing activities, with performance metrics saved in the models directory.

### :rocket: Getting Started

To get started with this project, clone this repository and install the required Python packages:

```bash
git clone https://github.com/AhmetY21/global-fishing-data-analysis.git
cd global-fishing-data-analysis
pip install -r requirements.txt
