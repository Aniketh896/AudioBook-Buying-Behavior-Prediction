# AudioBook-Buying-Behavior-Prediction
An Machine Learning algorithm to predict the **Audiobook Buying Behavior of the customers**

This is a Machine Learning Model that i created to predict the Audiobook Buying Behaviour of the Customers.

The dataset was collected over a period of 2.5 years, among which 2 years is used to accumulate the data and 6 months are used to calculate the targets.
The dataset is avilable in the `Audiobooks_data.csv` file.

***

The dataset consists of 4474 samples which we divide into:
- *Training Data: 3579 samples*
- *Validation Data: 447 samples*
- *Test Data: 448 samples*

The `Audiobook_preprocessing.ipynb` loads the data from the CSV file and preprocesses it (Balancing, Scaling, Standardization and Shuffling). After that, we save the Training Data, Validaton Data and the Test Data in  `Audiobooks_data_train.npz`,  `Audiobooks_data_train.npz`,  `Audiobooks_data_train.npz` respectively as tensors.  The `Audiobook Machine_Learning model.ipynb` is the model which we train using the data in the mentioned tensor files. 

**This particular model is 90% accurate** (*measured by the accuracy on the test data*)
