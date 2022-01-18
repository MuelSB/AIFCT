# Artificial Intelligence For Creative Technologies
This repository contains the two data sets used to train the Pix2Pix model (TrainingDataVersion1 and AdamsJacksonTestData) and the colourised results (AdamsJacksonColourisedResults.zip). 

The generator (latest_net_G.pth) and discriminator (latest_net_D.pth) models trained on the AdamsJacksonTestData.zip can be found in AdamsJacksonTrainedModel alongside text files stating the test and train options and the loss log.  

Code used to train the model and view results is in PythonCode.txt. The code was executed using Google Collaborate and expects training data to be located in the root of the user's Google Drive. Folder paths and names must be changed in the code to use different training data. By default AdamsJacksonTestData dataset will be used to train the model.

The report pdf is also available in AIReport.pdf.

### Project dependencies
Python 3.6  
PyTorch 1.4  
GPU
