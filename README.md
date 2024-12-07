# H3-cell-based-Indoor-Localization
An H3-cell-based narrow down approach is presented to find the User's location coordinates accurately and efficiently.
# DataSet
Source of dataset 1: https://zenodo.org/records/3748719
The Proposed scheme is evaluated on the dataset using WiFi RSS measurements collected on the 3rd and 5th floor of the library environment of Unviersitat Jaume I in Spain. The total area of both floors is about 308.4m2. Samples were collected by a trained person using Samsung Galaxy S3 smartphone over the span of 25 months. During the first month, 15 offline datasets were collected and we utilized them to train our model. The model performance is evaluated on the databases that were collected during the whole 25 months. Each floor contains 24 reference 218
points and 106 test points.

Source of dataset 2: https://zenodo.org/records/3748719
This is a hetrogenous Wi-Fi fingerprinting dataset that covers three buildings in different cities of china. Each building contains many floors.
# How to Use
1. download the dataset from the given source link
2. prepare the train and test files in .csv format
3. Use the feature extraction coding to extract the features from the dataset. 
4. use the code in the coarse positioning file to find the corase location of test samples or the user's residing H3-cell.
5. Train the support vector regressor on the sub-area containing the estimated coarse location H3-cell and its neighboring cells train dataset. 
6. Use the fine positioning code to find the user's fine location in the pre-selected sub-area. 


