# Waferdemo

Due to file size constrains I have uploaded the Files on the Google Drive.

Google Drive Link - https://drive.google.com/drive/folders/1wQs-QUpi5B7EVMzmnSJPOQxqZNcRDnnQ?usp=sharing

Try the app - http://waferfaultdetectionaws-env-1.eba-djpr3n2p.us-east-1.elasticbeanstalk.com/

(Due To Free Tier limitations, i have currently terminated the app)


# Poblem Statement:
The inputs of various sensors for different wafers have been provided. In electronics, a wafer (also called a slice or substrate) is a thin slice of semiconductor used for the fabrication of integrated circuits. The goal is to build a machine learning model which predicts whether a wafer needs to be replaced or not(i.e., whether it is working or not) based on the inputs from various sensors. There are two classes: +1 and -1.

+1 means that the wafer is in a working condition and it doesn’t need to be replaced.

-1 means that the wafer is faulty and it needs to be replaced.

# Data Description:
The client will send data in multiple sets of files in batches at a given location. Data will contain Wafer names and 590 columns of different sensor values for each wafer. The last column will have the "Good/Bad" value for each wafer.

"Good/Bad" column will have two unique values +1 and -1.

"+1" represents Good wafer.

"-1" represents Bad Wafer.

Apart from training files, we also require a "schema" file from the client, which contains all the relevant information about the training files such as: Name of the files, Length of Date value in FileName, Length of Time value in FileName, Number of Columns, Name of the Columns, and their datatype.
