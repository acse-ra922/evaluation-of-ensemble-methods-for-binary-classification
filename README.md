# Evaluation of Ensemble Methods for Binary Classification

This project aims to evaluate ensemble methods on their accuracy and time complexity while making classifying an asteroid as hazardous or not based on various features of the celestial object. The dataset used for this purpose contains information about 9083 unique asteroids and their characteristics. The features in the dataset are as follows:

**id**: Unique identifier of the asteroid.

**name**: Name of the asteroid.

**est_diameter_min**: Estimated minimum diameter of the asteroid (in kilometers).

**est_diameter_max**: Estimated maximum diameter of the asteroid (in kilometers).

**relative_velocity**: The relative velocity of the asteroid with respect to Earth (in kilometers per hour).

**miss_distance**: The distance at which the asteroid will pass by Earth (in kilometers).

**orbiting_body**: The celestial body that the asteroid is orbiting (in this case, all are orbiting Earth).

**sentry_object**: A boolean value indicating whether the asteroid is on the Sentry Impact Risk Table (True if it is, False otherwise).

**absolute_magnitude**: The absolute magnitude of the asteroid, which is a measure of its intrinsic brightness.

The dataset provides valuable insights into the physical properties and trajectory of each asteroid. By analyzing these features, the project aims to identify the machine learning model that can most accurately predict whether an asteroid poses a hazard to Earth. This information can be crucial for space agencies and researchers, enabling them to assess potential threats and develop mitigation strategies to ensure the safety of our planet. Additionally, this also helps us draw a comparison between different ensemble methods and their advantages and disadvantages.


Repository Structure:

1. dataset: Contains the raw training data and unseen data for model evaluation.
2. data_processing_pipeline: Includes a Jupyter Notebook that outlines the data preprocessing and cleaning steps for the datasets.
3. cleaned_datasets: Stores the cleaned versions of the datasets, which have been processed using the data processing pipeline.
4. ensemble_methods: Comprises four separate Jupyter Notebooks, each dedicated to building a model using a distinct ensemble method for binary classification.
5. trained_models: Holds the serialized trained models (in pickle format) for each of the four ensemble methods.
6. evaluation_of_models: Features a Jupyter Notebook that generates predictions on unseen data using all four ensemble models, and performs a time analysis of each prediction method for comparison.

This structured repository provides a comprehensive overview of the process of evaluating various ensemble methods for binary classification tasks, from initial data processing to final model evaluation and comparison.
