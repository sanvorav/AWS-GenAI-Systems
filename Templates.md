# Templates

## Model Data Lineage

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

---

## Data Quality, Privacy, Access, and Integrity

### 1. Data Quality Form Template

**Data Quality Form**

| Field Name                | Description                                                                 | Placeholder Example                  |
|---------------------------|-----------------------------------------------------------------------------|--------------------------------------|
| **Data Source**           | The origin of the data (e.g., database, API, file).                         | `Database: MySQL, API: OpenWeather`  |
| **Data Collection Date**  | The date when the data was collected.                                       | `YYYY-MM-DD`                         |
| **Data Completeness**     | Percentage of missing values in the dataset.                                | `5% missing values`                  |
| **Data Consistency**      | Checks for consistency within the dataset (e.g., format, range).            | `All dates in YYYY-MM-DD format`     |
| **Data Accuracy**         | Measures of data accuracy (e.g., error rates, validation checks).           | `Error rate: 2%`                     |
| **Data Timeliness**       | How up-to-date the data is.                                                 | `Updated daily`                      |
| **Data Quality Issues**   | Any known issues with the data quality.                                     | `Outliers in temperature readings`   |

### 2. Data Privacy Form Template

**Data Privacy Form**

| Field Name                | Description                                                                 | Placeholder Example                  |
|---------------------------|-----------------------------------------------------------------------------|--------------------------------------|
| **Data Sensitivity**      | The sensitivity level of the data (e.g., public, confidential).              | `Confidential`                       |
| **Data Anonymization**    | Techniques used to anonymize the data.                                       | `Pseudonymization, Masking`          |
| **Data Encryption**       | Methods used to encrypt the data.                                            | `AES-256 encryption`                 |
| **Access Controls**       | Permissions and access controls for the data.                                | `Role-based access control`          |
| **Data Retention Policy** | How long the data is retained.                                               | `Retained for 1 year`                |
| **Compliance Standards**  | Standards and regulations the data complies with (e.g., GDPR, HIPAA).        | `GDPR, CCPA`                         |
| **Privacy Impact Assessment** | Assessment of the potential impact on privacy.                           | `Low, Medium, High`                  |

### 3. Data Access Form Template

**Data Access Form**

| Field Name                | Description                                                                 | Placeholder Example                  |
|---------------------------|-----------------------------------------------------------------------------|--------------------------------------|
| **Data Access Roles**     | Roles that have access to the data.                                          | `Admin, Analyst, Developer`          |
| **Access Permissions**    | Specific permissions granted to each role.                                   | `Read, Write, Execute`               |
| **Authentication Methods**| Methods used to authenticate users.                                          | `Multi-factor authentication`        |
| **Access Logging**        | Whether access to the data is logged.                                        | `Access logs enabled`                |
| **Data Sharing Policies** | Policies for sharing data with external parties.                             | `Data sharing agreements required`   |
| **Access Review Frequency** | How often access permissions are reviewed.                                 | `Quarterly`                          |
| **Incident Response Plan** | Plan for responding to unauthorized access incidents.                       | `Incident response team notified`    |

### 4. Data Integrity Form Template

**Data Integrity Form**

| Field Name                | Description                                                                 | Placeholder Example                  |
|---------------------------|-----------------------------------------------------------------------------|--------------------------------------|
| **Data Validation**       | Methods used to validate data integrity.                                     | `Checksums, Hashing`                 |
| **Data Backup**           | Frequency and methods of data backups.                                       | `Daily backups, Cloud storage`       |
| **Data Recovery Plan**    | Plan for recovering data in case of loss or corruption.                      | `Disaster recovery plan in place`    |
| **Data Integrity Checks** | Regular checks to ensure data integrity.                                     | `Monthly integrity checks`           |
| **Data Modification Logs**| Logs of any modifications made to the data.                                  | `Modification logs enabled`          |
| **Data Integrity Issues** | Any known issues with data integrity.                                        | `None reported`                      |
| **Audit Trails**          | Records of data access and modifications for auditing purposes.              | `Audit trails maintained`            |
