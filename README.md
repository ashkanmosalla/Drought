<img src="C:\Users\Admin\Desktop\project\GitHub\Drought\DALL·E 2024-.webp" alt="logo" width="400"/>

# Drought Susceptibility Mapping Using Deep Learning for Canada

## Project Overview

This project aims to utilize deep learning to map drought susceptibility in Canada. Leveraging a geospatial database and applying an Artificial Neural Network (ANN) model, we predict drought probabilities across various points in droughted and non-droughted areas. Our approach accounts for multiple climate change scenarios, making the study significant for future planning and mitigation strategies.

## Dataset

The dataset comprises droughted points extracted from Canadian drought annual map and various geospatial features. The data has been split into an 80-20 ratio for training and testing purposes. the database includes the following features:
- Slope
- Aspect
- Soil Moisture
- Temperature (July Temperature)
- Distance from Lake
- Distance from Road
- Precipitation
- NDVI (Normalized Difference Vegetation Index)
- TWI (Topographic Wetness Index)
- Distance from River
- Elevation
These features are categorized into numeric values, indicating specific categories.

## Climate Change Scenarios

We have modeled the following climate change scenarios for the geospatial database:
- 2024-2050
- 2050-2070
- 2070-2100

## Methodology

After thorough data preprocessing and exploratory data analysis (EDA), we conducted multi-collinearity analysis and utilized the Random Forest feature importance technique, which resulted in the exclusion of the temperature feature. Deep Artificial Neural Network (ANN) model was then trained to generate prediction maps, indicating drought probabilities for each point.

## Acknowledgments

This section is dedicated to individuals, organizations, and institutions that contributed significantly to the development and success of this project. We extend our heartfelt gratitude to:

- **Dr. Khabat Khosravi**, for his invaluable guidance in methodologies and data.
- **Alireza Shahvaran**, for his expertise in data collection under different climate change scenarios.
