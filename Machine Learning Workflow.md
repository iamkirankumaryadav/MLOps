# Machine Learning Workflow

- ML workflows define which phases are implemented during a machine learning project.
- Phases: data collection, data pre-processing, building datasets, model training and refinement, evaluation, and deployment to production.
- You can automate some aspects of the ML operations workflow, such as model and feature selection

## Understanding the Machine Learning Workflow
- ML workflows define the steps initiated during a particular ML implementation.
- ML workflows vary by project, but four basic phases are typically included.

### Gathering ML data
- Gathering data is one of the most important stages of ML workflows.
- During data collection, you are defining the potential usefulness and accuracy of your project with the quality of the data you collect.
- To collect data, you need to identify your sources and aggregate data from those sources into a single dataset.
- This could mean streaming data from IoThings sensors, downloading open source data sets, or constructing a data lake from assorted files, logs, or media.

### Data Pre-processing
- Once your data is collected, you need to pre-process it.
- Pre-processing involves cleaning, verifying, and formatting data into a usable dataset.
- If you are collecting data from a single source, this may be a relatively straightforward process.
- However, if you are aggregating several sources you need to make sure that data formats match, that data is equally reliable, and remove any potential duplicates.

### Building Datasets
- This phase involves breaking processed data into three datasets—training, validating, and testing:
- Training set—used to initially train the algorithm and teach it how to process information. Model learns parameters and features. 
- Validation set—used to estimate the accuracy of the model. This dataset is used to finetune model parameters.
- Test set—used to assess the accuracy and performance of the models. This set is meant to expose any issues or mistrainings in the model.

### Training and Refinement
- Once you have datasets, you are ready to train your model.
- This involves feeding your training set to your algorithm so that it can learn appropriate parameters and features.
- Once training is complete, you can then refine the model using your validation dataset.
- This may involve modifying or discarding variables and includes a process of tweaking model-specific settings (hyperparameters) until an acceptable accuracy level is reached.

### ML Evaluation
- Finally, after an acceptable set of hyperparameters is found and your model accuracy is optimized you can test your model.
- Testing uses your test dataset and is meant to verify that your models are using accurate features.
- Based on the feedback you receive you may return to training the model to improve accuracy, adjust output settings, or deploy the model as needed.
