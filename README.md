# NN-Image_Classification

This is a simple Neural Network that classifies the number of the image. The input is a matrix that represents a image of a hand-written number. The output is the number of that image, from 0 to 9.  

How to run:
1. Open google colab in the browser, click File -> Upload Notebook -> choose S2S_Enc_Dec_Att_RNN.ipynb  
2. Click runtime -> Run all  
3. At DATA block, upload 4 files: "test_data.gz", "test.labels.gz", "train_data.gz", "train_labels.gz".  
4. It takes approximate 5 hours to train the model.  
5. The output should show the image and its class, and also the average loss and accuracy for each epoch.  
