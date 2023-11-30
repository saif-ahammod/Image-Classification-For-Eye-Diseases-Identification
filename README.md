As we mentioned before our project has two phases. in each phase there are 4 architucture used and 3 .ipynb file.
How to run all six files detailed instruction is given here.
------------------------------------------------------------------------------------------------------------------
Dataset link: www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification

1. At first download the dataset from the given dataset link and keep it in your pc. Remember you need the path of the dataset several times to run the project
------------------------------------------------------------------------------------------------------------------
# Phase 1 > 1. Resnet50 and DenseNet121.ipynb

Step 1: Go to phase 1 folder and run the mentioned file using VS Code or jupyter notebook

Step 2: Run the cell "1. Importing The Required Libraries" which will import all the necessary liberary

Step 3: Next in cell "2. Importing Dataset" give the dataset path you downloaded earlier

Step 4: Run all the cell from 3 to 4. This will give you the information of the dataset and will assign some important parameter

Step 5: In cell "5.1 Train & Test Partiotioning" give two empty folders path one for test and another for train dataset

Step 6: THen run all the cell from 5.2 to 7.4.8 it will run and build Resnet 50 and Densenet121 model
------------------------------------------------------------------------------------------------------------------
# Phase 1 > 2. InceptionV3.ipynb

Step 1: Go to phase 1 folder and run the mentioned file using VS Code or jupyter notebook

Step 2: Run the cell "1. Installations & Importing Required Libraries and Packages" which will import all the necessary liberary

Step 3:Next in cell "2. Import Dataset" give the dataset path you downloaded earlier

Step 4: Next in cell "3. Dataset Statistics" give the dataset path you downloaded earlier

Step 5: Next in cell "5. Splitting" give the dataset path you downloaded earlier and also define paths for your training, validation, and test sets

Step 6: Then run all the cell to the end to build the inception 
------------------------------------------------------------------------------------------------------------------
# Phase 1 > 3. VGG16.ipynb

Step 1: Go to phase 1 folder and run the mentioned file using VS Code or jupyter notebook

Step 2: Run the cell "1. Installations & Importing Required Libraries and Packages" which will import all the necessary liberary

Step 3:Next in cell "2. Import Dataset" give the dataset path you downloaded earlier

Step 4: Next in cell "3. Data Visualization" give the dataset path you downloaded earlier

Step 5: Next in cell "4. Splitting", "5. Data Partitioning (Training & Testing)" and "6. VGG16 Model" give the dataset path you downloaded earlier and also define paths for your training, validation, and test sets

Step 6: Then run all the cell to the end to build the inception 
------------------------------------------------------------------------------------------------------------------
# Phase 2 > 4. Resnet50 and DenseNet121 After Image Processing.ipynb
Step 1: Go to phase 2 folder and run the mentioned file using VS Code or jupyter notebook

Step 2: Run the cell "1. Importing The Required Libraries" which will import all the necessary liberary

Step 3: Next in cell "2. Importing Dataset" give the dataset path you downloaded earlier

Step 4: Run all the cell from 3.1 to 3.4. This will give you the information of the dataset

Step 5: In cell "4.1.1 Applying Histogram Equalization" give a empty folders path to "output_dir" where you want to keep the dataset after histogram equalization and then run to 4.1.2 and in 4.2.2 set the "local_path" where you keept the dataset after histogram equalization.

Step 6: In cell "4.2.1 Applying Noise Cancellition" give a empty folders path to "output_dir" where you want to keep the dataset after noise cancelition and set histogram equalization data path to "local_path" and thhen in 4.2.2 set the "local_path" where you keept the dataset after noise cancelition

Step 7: In cell "4.3.1 Applying Image Sharping" give a empty folders path to "output_dir" where you want to keep the dataset after image sharpining and set noise cancelition data path to "local_path" and then run to 4.3.2 set the "local_path" where you keept the dataset after Image Sharping

Step 8: In cell "4.4.1 Augmenting data" give a empty folders path to "output_dir" where you want to keep the dataset after augmentation and set image sharpning data path to "local_path" and then run to 4.4.2 set the "local_path" where you keept the dataset after Image augmentation

Step 9: Then run all the cell from 4.4.2 to 5.1 it will run and build Resnet 50 and Densenet121 model

Step 10:In cell "5.1 Train & Test Partiotioning" and "5.2 Count & Visualize Data After Partition" give two empty folders path one for test and another for train dataset

Step 11: Then run all the cell to the end to build the inception 
------------------------------------------------------------------------------------------------------------------
# Phase 2 > 5. InceptionV3 After Image Processing.ipynb
Step 1: Go to phase 1 folder and run the mentioned file using VS Code or jupyter notebook

Step 2: Run the cell "1. Installations & Importing Required Libraries and Packages" which will import all the necessary liberary

Step 3:Next in cell "2. Import Dataset" give the dataset path of the folder where you kept data after augmention

Step 4: Next in cell "3. Dataset Statistics" give the dataset path of the folder where you kept data after augmention

Step 5: Next in cell "5. Splitting" give the dataset path of the folder where you kept data after augmention and also define paths for your training, validation, and test sets

Step 6: Then run all the cell to the end to build the inception 
------------------------------------------------------------------------------------------------------------------
# Phase 2 > 6. VGG16 After Image Processing.ipynb
Step 1: Go to phase 1 folder and run the mentioned file using VS Code or jupyter notebook

Step 2: Run the cell "1. Installations & Importing Required Libraries and Packages" which will import all the necessary liberary

Step 3:Next in cell "2. Import Dataset" give the dataset path of the folder where you kept data after augmention

Step 4: Next in cell "3. Data Visualization" give the dataset path of the folder where you kept data after augmention

Step 5: Next in cell "4. Splitting", "5. Data Partitioning (Training & Testing)" and "6. VGG16 Model" give the dataset path of the folder where you kept data after augmention and also define paths for your training, validation, and test sets

Step 6: Then run all the cell to the end to build the inception 
------------------------------------------------------------------------------------------------------------------
I hope this will help you to run all the file thank you.....