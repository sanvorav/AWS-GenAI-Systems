### 1. Data Lineage Form Template

**Data Lineage Form**

| Field Name                | Description                                                                 | Placeholder Example                  |
|---------------------------|-----------------------------------------------------------------------------|--------------------------------------|
| **Data Source**           | The origin of the data (e.g., database, API, file).                         | `Database: MySQL, API: OpenWeather`  |
| **Data Ingestion Date**   | The date when the data was ingested.                                        | `YYYY-MM-DD`                         |
| **Data Transformation**   | Description of any transformations applied to the data.                     | `Normalization, Aggregation`         |
| **Data Storage Location** | Where the data is stored after ingestion.                                   | `S3 Bucket, Data Warehouse`          |
| **Data Consumers**        | Entities or systems that consume the data.                                  | `Analytics Team, ML Model`           |
| **Data Quality Checks**   | Any quality checks performed on the data.                                   | `Missing Values Check, Duplicates`   |
| **Data Lineage Diagram**  | Visual representation of the data flow from source to destination.          | `Link to Diagram`                    |

### 2. Cataloging Form Template

**Data Catalog Form**

| Field Name                | Description                                                                 | Placeholder Example                  |
|---------------------------|-----------------------------------------------------------------------------|--------------------------------------|
| **Dataset Name**          | The name of the dataset.                                                    | `Customer Transactions`              |
| **Dataset Description**   | A brief description of the dataset.                                         | `Contains customer purchase data`    |
| **Data Owner**            | The person or team responsible for the dataset.                             | `Data Engineering Team`              |
| **Data Source**           | The origin of the data (e.g., database, API, file).                         | `Database: MySQL, API: OpenWeather`  |
| **Data Schema**           | The structure of the dataset (e.g., columns, data types).                   | `Column1: String, Column2: Integer`  |
| **Data Sensitivity**      | The sensitivity level of the data (e.g., public, confidential).              | `Confidential`                       |
| **Data Access Controls**  | Permissions and access controls for the dataset.                            | `Read-Only, Admin Access`            |
| **Data Update Frequency** | How often the data is updated.                                              | `Daily, Weekly`                      |
| **Data Quality Metrics**  | Metrics used to assess the quality of the data.                             | `Accuracy, Completeness`             |
| **Data Usage**            | How the data is used within the organization.                               | `Reporting, Machine Learning`        |

### 3. Model Card Form Template

**Model Card Form**

| Field Name                | Description                                                                 | Placeholder Example                  |
|---------------------------|-----------------------------------------------------------------------------|--------------------------------------|
| **Model Name**            | The name of the model.                                                      | `Customer Churn Prediction`          |
| **Model Version**         | The version of the model.                                                   | `v1.0`                               |
| **Model Description**     | A brief description of the model and its purpose.                           | `Predicts customer churn`            |
| **Model Owner**           | The person or team responsible for the model.                               | `Data Science Team`                  |
| **Training Data**         | Description of the data used to train the model.                            | `Customer transaction data`          |
| **Training Date**         | The date when the model was trained.                                        | `YYYY-MM-DD`                         |
| **Model Architecture**    | The architecture of the model (e.g., neural network, decision tree).        | `Random Forest`                      |
| **Performance Metrics**   | Metrics used to evaluate the model's performance.                           | `Accuracy, Precision, Recall`        |
| **Model Limitations**     | Any known limitations of the model.                                         | `Limited to historical data`         |
| **Model Usage**           | How the model is used within the organization.                              | `Customer retention strategies`      |
| **Model Fairness**        | Assessment of the model's fairness and any bias mitigation strategies.      | `Fairness metrics, Bias mitigation`  |
| **Model Lineage Diagram** | Visual representation of the model's development and deployment process.    | `Link to Diagram`                    |

