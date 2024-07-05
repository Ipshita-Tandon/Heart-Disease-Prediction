# Heart-Disease-Prediction

This project aims to analyse a patient's health and predict whether a patient is at risk of having a heart failure using machine learning algorithms. The project leverages a detailed dataset containing various attributes related to heart health, such as age, sex, cholesterol levels, blood pressure and exercise habits. Here I analyse patient data and make predictions using 4 machine learning models and evaluate their relative performance.

## Dataset Description
The project utilizes a dataset obtained from Kaggle containing anonymized patient information, including age, sex, cholesterol levels, blood pressure exercise habits, and medical history. A detailed description of the dataset and what each attribute signifies is presented below:

![image](https://github.com/Ipshita-Tandon/Heart-Disease-Prediction/assets/120296010/22126d08-b156-466d-aa6d-322f22803138)

## Libraries used
1. Numpy: Efficient handling of large arrays and matrices, with mathematical functions for operations.
2. Pandas: Data manipulation and analysis, providing data structures like DataFrames.
3. Matplotlib: Plotting library for creating appealing and interactive visualizations.
4. Seaborn: Statistical data visualization based on matplotlib, with enhanced aesthetics.
5. Scikit-learn: Models and preprocessing tools for machine learning tasks.
6. TensorFlow, Keras: Used for building and training deep learning models.

## Data Preprocessing
1. Importing Libraries: Essential Python libraries like pandas, numpy, matplotlib, seaborn, tensorflow and keras are imported.
2. Data visualization: Matplotlib and seaborn are used for data visualization and display relationships among attributes.
3. Outlier detection: Removes datapoints that significantly deviate from the rest of the data to enhance model accuracy.
4. Label encoding: Technique used to convert objects and strings to numerical format interpretable by the model.
5. Feature scaling: Normalize features varying in magnitude, range, and units on a common scale for evaluation.

## Machine Learning Models
The project evaluate patient health by using 4 machine learning models namely:
1. Logistic regresssion : 0.847826%
2. Random Forest : 0.880435%
3. Support Vector Machine : 0.880435
4. Convoluted Neural Network : 0.875000

## Performance Evaluation
Performance of machine learning models is evaluated based on below metrics:
1. Accuracy score: measures ratio of correct predictions to total predictions made.
2. Classification report: Provides precision, recall, F1-score, and support for each class.
3. Confusion matrix: Table that summarizes performance by showing true and false positives and negatives.

## Contributing
Contributions to this project are encouraged and welcomed. For suggestions, feature requests, or bug reports, please submit an issue or fork the repository and submit a pull request with proposed changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details

## Contact Me
For any questions or feedback, please contact me at:
* Email: ipshitatandon@gmail.com
* Linkedin: https://www.linkedin.com/in/ipshita-tandon-505157257/
* GitHub: https://github.com/Ipshita-Tandon/heart-disease-prediction
