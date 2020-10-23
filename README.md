# Machine-Learning-and-Content-Analytics

The Data can be downloaded from the below link:
https://drive.google.com/drive/folders/1n2dPFbp17Odsb7l2GaUsgdRofW8WNaeW?usp=sharing


This file contains: 
- argument file with all the documents as input in the train dataset
- argument_test with all the documents as input for the test dataset
- Model_CNN365 file with contains all the files needed for someone in order to use the best trained CNN model and its weights. To do so he/she needs to load the model through Keras as described in the code ipynb file (Main_code.ipynb). 

Important note: The weights of the best trained CNN Model downloaded differ from those those presented in the final report/code (report doc file and main code file). This was due to the fact that the computation of weights was the last addition to our code, that's why we have to rerun it and the results change (eg. Accuracy in test set = 0.67 instead of 0.69). Because of time limitation and deadline pressure we weren't able to update all numbers and metrics. 

Code files:
- Main_code.ipynb includes all the main code from data import, preparation/cleansing, building and running RNN and CNN models as well as evaluation measurements 
- CNN_parameter_testing.ipynb file was created only for testing the different (hyper-)paremeter values of the CNN model. The first part of the code is the same with the main code file. The testing begins from the «Build Text CNN Model» section.
- ML_MASTER_TEST.ipynb includes the code for accessing the best trained CNN model in the whole dataset (without splitting in train and validation parts).The first part of the code is the same with the main code file. Further to the "winning" model the jupyter also includes the code for the blind test dataset. The code reads the folder of the testing files and for every file it exports a new file with the same filename and the results of the CNN argument detection per row. The results have beeb uploaded in Microsoft Team's folder.

report.pdf includes the report describing all the current project end to end. Presentation of target, results, bibliography etc are included. 

The group consists of the below members:
- Anastasios Pliatsikas
- Stavros Konstantinos Gardelis
- Athanasia Eleni Sideri
