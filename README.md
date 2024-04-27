#Product Price Prediction using LSTM with PySpark

This project demonstrates the use of LSTM (Long Short-Term Memory) neural networks with PySpark for predicting product prices based on features like MRP and star rating. The dataset used contains apparel data with various attributes including product MRP, star rating, and sale price.


*Dataset*
The dataset used for this project is the Decathlon Apparel Data available on Kaggle. It consists of information about Decathlon apparel products, including product names, MRP, star ratings, and sale prices.


*Requirements*

->Python 3.x

->Pandas

->NumPy

->Scikit-learn

->TensorFlow

->PySpark


*Usage*

* Clone the repository or download the script files.

* Install the required dependencies using pip install -r requirements.txt.

* Replace 'file_path' in the script with the actual path to your dataset.

*Run the script in a Python environment capable of running PySpark code.


*Workflow*

* Load the dataset and explore its structure.

* Preprocess the data, including handling missing values, scaling features, and creating sequences for RNN.

* Split the data into training and testing sets.
Build an LSTM model using PySpark's TensorFlow integration.
Train the model on the training data and evaluate its performance.
Make predictions on the testing data and evaluate the model's accuracy.
Print sample predictions and identify the product with the highest predicted price.
