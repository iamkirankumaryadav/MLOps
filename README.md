# **MLOps (Machine Learning Operations)**

- A set of practices that aim to streamline and automate the process of deploying and managing ML models in production environments.
- **MLOps** is an ML engineering culture and practice that aims at unifying ML development (Dev) and ML Operations (Ops).

### **Key components of MLOps include:**

1. **Data management:** Efficiently handling, cleaning, and preparing data for model training and deployment.
2. **Model development:** Building and training ML models using various algorithms and techniques.
3. **Model deployment:** Deploying trained models into production environments, making them accessible for real-time predictions.
4. **Monitoring:** Continuously tracking model performance and identifying potential issues or degradation.
5. **Automation:** Automating repetitive tasks like data ingestion, model training, and deployment to improve efficiency.

### **Benefits of MLOps:**
1. **Faster time to market:** Accelerate the process of getting ML models into production skipping the manual process.
2. **Improved model quality:** Ensure that models are reliable, consistent and perform as expected in real-world scenarios.
3. **Enhanced collaboration:** Foster collaboration between data scientists, engineers, and other stakeholders involved in the ML lifecycle.
4. **Reduced operational costs:** Streamline the management and maintenance of ML models by reducing cost and time.
5. **Increased agility:** Enable organizations to respond quickly to changing business needs and market conditions.

## **MLOps Tools & Frameworks:**

### 1. **Kubeflow:** 
- A platform for building and deploying ML workflows on Kubernetes.

**Kubeflow Central Dashboard**
![Kubeflow Central Dashboard](https://github.com/iamkirankumaryadav/MLOps/blob/19b1fc0e35e6848bf1d946b1d9ccde289154da65/Image/Kubeflow%20Dashboard.png)

**Kubeflow Pipelines**
![Kubeflow Pipelines](https://github.com/iamkirankumaryadav/MLOps/blob/19b1fc0e35e6848bf1d946b1d9ccde289154da65/Image/Kubeflow%20Pipeline%20Runs.png)

### 2. **MLflow:** 
- A platform for managing the ML lifecycle, including UI, evaluation, tracking, model registry, and deployment.
- Training + Hyperparameter Tuning (Optimization) + Evaluation + UI Visualization + Tracking + Validation + Registry + Deployment.

### 3. **TensorFlow Extended (TFX):** 
- A scalable, flexible, and extensible platform for building, deploying, and monitoring ML pipelines.

### 4. **AWS SageMaker:** 
- A fully managed platform by AWS for ML that provides tools for building, training, and deploying models.

### 5. **Azure Machine Learning:** 
- A cloud-based platform for building, training, and deploying ML models.

### **All the steps of the ML system**
- ETL (Extraction, Transformation, Load)
- Development
- Training, Optimization, Hyperparameter, Fine Tuning, Retraining
- Testing, Building, Promoting, Deployment
- Monitoring, Automation, Integration, Releasing
- Sustenance
- Infrastructure Management

### **MLOps Framework**

**Job Orchestration**: Which steps need to be executed first? define the steps and workflow.

- Data Ingestion (Collecting data from various sources)
- Data Validation (Handling missing data, outliers, duplicates)
- Data Transformation (Normalization, encoding, conversion, etc)
- Model (Build, train, tune, retrain, optimize, hyperparameter tuning, refining, deploy)
- Model Analysis (Evaluation, validation, versioning, registry)
- Serving (Integrate with the required applications and services)
- Logging (Metric, errors, workflow, lineage, audit etc)
