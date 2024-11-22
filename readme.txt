COMP-6721: README for group OB_12

The submission consists of the following :

1.FINAL_DATASET:
•	ClothMask       # this folder contains the images of person with Cloth Mask   
•	mask_worn_incorrectly		# this folder contains the images of person who wore the mask incorrectly 
•	N95	# this folder contains the images of person wearing N95 masks
•	SurgicalMask     # this folder contains the images of person wearing Surgical Mask   
•	WithoutMask    # this folder contains the images of person Without Mask

2. Link: The link to the complete dataset: https://drive.google.com/drive/folders/1Xz1z57HWVDhycS2ecdym-aHVgC_j4yqQ?usp=sharing

3. Procedure: For training our model, download the ipynb file and follow the sequence:

Download the comp6721_phase2 python file for the k-fold validation, model_comparison file for the coparison between the models and comp6721_biastesting for testing the bias of the dataset

and upload it in a jupyter/colab notebook.

•	Importing the necessary libraries
•	Importing the training data 
•	Importing the testing data 
•	Converted training dataset to batches 
•	Converted testing dataset to batches 
•	Train the CNN function (train_CNN_Model())
•	Compute evaluation metrics – Precision, Recall and Accuracy
   

