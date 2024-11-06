# SD-Homelessness-Program-Analysis
## Summary
WIP
## Data Cleaning Transparency
### Data Pipeline

| **INPUT DATASET(S)**  | **DATA CLEANING SCRIPT** | **OUTPUT DATASET(S)** |
| ------------- | ------------- | ------------- |
| `CityExpendituresRaw.csv`  | `raw_data_cleaning.ipynb`  | `processed.csv`  |
| `processed.csv`  | `updated_dataset.ipynb`  | `updated_dataset.csv`  |
| `updated_dataset` `PITCount.csv`  | `RP_preprocessing_20241025.ipynb`  | `expenditures_and_PIT.csv` |
| `expenditures_and_PIT.csv` | `pivoted_dataset (1).ipynb` | `pivoted_dataset.csv`  |
| `expenditures_and_PIT.csv` `PITCount.csv`*  | `RP_preprocessing_20241025.ipynb`  | `pivoted_and_PIT.csv`  |
| `pivoted_and_PIT.csv` `expenditures_and_PIT.csv`  | `pivoted_pit_grantee.ipynb`  | `pivoted_pit_grantee.csv`  |

### Program Name Dictionary
- 

## Data Analysis
