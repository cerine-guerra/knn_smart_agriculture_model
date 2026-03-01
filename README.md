# knn_smart_agriculture_model
The Smart Agriculture knn model is an application designed to provide farmers with personalized advice on crop management, pest control, and irrigation scheduling. By leveraging machine learning models, the system analyzes various environmental and soil parameters to recommend the most suitable crops for cultivation. 

## Dataset
The dataset used for this project is sourced from Kaggle: [Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset).

### Features
- **N (Nitrogen)**: Nitrogen content in the soil
- **P (Phosphorus)**: Phosphorus content in the soil
- **K (Potassium)**: Potassium content in the soil
- **temperature**: Temperature in degree Celsius
- **humidity**: Relative humidity in %
- **ph**: pH value of the soil
- **rainfall**: Rainfall in mm

### Target
- **label**: Type of crop to be grown

## Usage

1. **Run Jupyter Notebook**

    ```bash
    jupyter notebook
    ```

2. **Open the Notebook**

    In the Jupyter Notebook interface, open `notebooks/Smart_Agriculture_knn_model.ipynb` to explore the analysis, model training, and predictions.

## Project Structure

- `data/`: Contains the dataset used for training and testing.
- `notebooks/`: Jupyter notebooks for data analysis and model building.
- `models/`: Saved machine learning models.
- `scripts/`: Python scripts for data processing and model training.
- `requirements.txt`: List of required Python libraries.
