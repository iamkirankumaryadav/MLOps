# MLOps (Machine Learning Operations)
- A set of practices that aim to streamline and automate the entire ML lifecycle, from development to deployment and maintenance.

### **All the steps of the ML system**
- Data Management: Extract, transform, load, ingest (Data from multiple sources) 
- Data Pipeline: Validate, clean, standardise, curate, etc.
- Feature Engineering: Select, extract, and create new features.
- Model Development: Code, train, validate, evaluate, optimize, fine-tune, retrain, hyperparameter tuning, etc.
- Model Deployment: Deploy, containerise, package, code versioning (GitHub, Gitlab, Bit Bucket), CI/CD, etc.
- Monitor, Automate, integrate, release, track, metrics, etc.
- Serve: UI (streamlit), API, application for the users, etc
- Sustenance and Infrastructure Management

### **Benefits of MLOps:**
1. **Faster time to market:** Accelerate getting ML models into production skipping the manual process.
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

### **MLOps Framework**

**Job Orchestration**: Which steps need to be executed first? define the steps and workflow.

- Data Ingestion (Collecting data from various sources)
- Data Validation (Handling missing data, outliers, duplicates)
- Data Transformation (Normalization, encoding, conversion, etc)
- Model (Build, train, tune, retrain, optimize, hyperparameter tuning, refining, deploy)
- Model Analysis (Evaluation, validation, versioning, registry)
- Serving (Integrate with the required applications and services)
- Logging (Metric, errors, workflow, lineage, audit etc)
