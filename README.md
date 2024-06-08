# Alphabet Soup Funding Prediction Analysis

## Purpose

The goal of this analysis is to develop a binary classifier using a deep learning neural network to predict the success rate of applicants for funding from Alphabet Soup, a nonprofit organization. The dataset provided contains information on over 34,000 organizations, including metadata such as:

## Application type
- Affiliated sector of industry
- Government organization classification
- Use case for funding
- Income classification
- Funding amount requested
- Effectiveness of fund usage
- Analysis Process

## Data Preprocessing
- Dropping Unnecessary Columns: Columns not contributing to the model’s predictive power are removed.
- Encoding Categorical Variables: Converting categorical variables into numerical values using techniques like one-hot encoding.
- Splitting Data: Dividing the dataset into training and testing sets to evaluate model performance.
- Model Design and Training
- Neural Network Design: Creating a neural network model using TensorFlow and Keras.
- Training the Model: Training the model on the training dataset.
- Evaluation: Assessing the model's performance using metrics like loss and accuracy.
- Optimization Attempts
- To improve the model’s accuracy, several optimization techniques were employed:

- Adjusting input data
- Adding more neurons and hidden layers
- Using different activation functions
- Changing the number of epochs
- The target was to achieve a predictive accuracy higher than 75%.

## Results

The deep learning model developed was able to achieve a predictive accuracy of 74% in classifying the success of organizations funded by Alphabet Soup based on their features. Despite several optimization attempts, including:

- Dropping columns
- Binning categorical variables
- Adding hidden layers and neurons
- Trying different activation functions
- The desired predictive accuracy of 75% was not reached.

## Conclusion

While the model achieved a reasonable level of accuracy, further optimization is required to surpass the 75% accuracy target. Considering the limitations, it may be beneficial to explore alternative models known for their effectiveness in binary classification problems. These models can handle both numerical and categorical variables, and manage outliers and imbalanced datasets effectively, which might be present in this dataset.

The optimized model was saved as an HDF5 file for future reference and further improvements.

By exploring and testing alternative models, there is potential to achieve higher accuracy without extensive optimization attempts. This analysis lays the foundation for further improvements and exploration in predictive modeling for funding success rates.