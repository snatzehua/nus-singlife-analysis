# Model for Product Purchases

## Overview

This project builds a predictive model for client-agent matching using customer, policy, and agent data. The dataset is merged from multiple sources to analyze key factors influencing customer decisions. The model aims to provide insights into customer behavior and optimize sales strategies.

**Note: dataset omitted due to confidentiality agreement**

## Installation

1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd project_directory
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Ensure you have Jupyter Notebook installed to run the `.ipynb` file:
   ```bash
   pip install notebook
   ```

## Dataset

The project uses three primary datasets:

- **Agents Data**: Contains details of agents handling policies.
- **Policies Data**: Includes policy details purchased by customers.
- **Clients Data**: Holds demographic information about clients.

These datasets are merged on relevant keys (`agntnum` for agents and `secuityno` for clients) to create a comprehensive dataset. The datasets have not been included due to an NDA with Singlife and NUS SDS.

## Methodology

1. **Data Preprocessing**:
   - Merging datasets using `pandas.merge()`
   - Handling missing values by filling with median values
   - Mapping categorical age groups to numerical values
2. **Feature Engineering**:
   - Extracting age group details
   - Calculating household size and economic status
3. **Model Training**:
   - Using machine learning techniques (to be detailed further)
   - Evaluating performance using appropriate metrics

## Usage

To run the analysis:

1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Load and execute the `model_prod_predict.ipynb` file.

## Future Improvements

- Enhance feature engineering for better predictions
- Explore different machine learning models
- Optimize model performance with hyperparameter tuning

## Contributors

- Kieran Ho Cheng Hong

## License

This project is licensed under the MIT License.
