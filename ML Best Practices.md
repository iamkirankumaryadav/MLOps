# What Are the ML Best Practices for Efficient Workflows?

### Define the project
- Carefully define your project goals before starting to ensure your models add value to a process rather than redundancy.
- When defining your project, consider the following aspects:
- What is your current process—typically models are designed to replace an existing process.
- Understanding how the existing process works, what its goals are, who performs it, and what counts as success are all important.
- Understanding these aspects lets you know what roles your model needs to fill, what restrictions might exist in implementation, and what criteria the model needs to meet or exceed.
- What do you want to predict—carefully defining what you want to predict is key to understanding what data you need to collect and how models should be trained.
- You want to be as detailed as possible with this step and make sure to quantify results.
- If your goals aren’t measurable you’ll have a hard time ensuring that each is met.
- What are your data sources—evaluate what data your current process relies on, how it’s collected and in what volume.
- You should determine what specific data types and points you need to form predictions from those sources.

### Find an approach that works
- The goal of implementing ML workflows is to improve the efficiency and/or accuracy of your current process.
- To find an approach that achieves this goal you need to:

1. Research—before implementing an approach, you should spend time researching how other teams have implemented similar projects.
2. You may be able to borrow methods they used or learn from their mistakes, saving yourself time and money.
3. Experiment—whether you have found an existing approach to start from or created your own, you need to experiment with it.
4. This is essentially the training and testing phases of your model training.

2. Build a full-scale solution
- When developing your approach, your result is typically a proof-of-concept.
- However, you need to be able to translate this proof into a functional product to meet your end goal.
- To transition from a proof to deployable solution, you need the following:
- A/B testing—enables you to compare your current model with the existing process.
- This can confirm or deny whether your model is effective and able to add value to your teams and users.

3. Machine learning API—creation
- An API for your model implementation is what enables it to communicate with data sources and services.
- This accessibility is especially important if you plan to offer your model as an ML service.

3. User-friendly documentation
- Documentation of code, methods, and how to use the model.
- If you want to create a marketable product it needs to be clear to users how they can leverage the model, how to access its results, and what kind of results they can expect.

## Automating Machine Learning Workflows
- Automating ML workflows enables teams to more efficiently perform some of the repetitive tasks involved in model development.
- There are many modules and an increasing number of platforms for this, sometimes referred to as autoML.

### What is Automated Machine Learning?
- AutoML essentially applies existing ML algorithms to the development of new models.
- Its purpose is not to automate the entire process of model development.
- Instead, it is to reduce the number of interventions that humans must make to ensure successful development.
- AutoML helps developers get started with and complete projects significantly faster.
- It also has the potential to improve deep learning and unsupervised ML training processes, potentially enabling self-correction in developed models.

### What Can You Automate?
- While it would be great to be able to automate all aspects of ML operations, this currently isn’t possible.

### What can be reliably automated includes:
- Hyperparameter optimization—uses algorithms like grid search and random search to test combinations of pre-defined parameters and find the optimal combination.
- Model selection—the same dataset is run through multiple models with default hyperparameters to determine which is best suited to learn from your data.
- Feature selection—tools select the most relevant features from pre-determined sets of features.
