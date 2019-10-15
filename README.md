# LunarClassification
Hackerearth Image Classification Challenge



Lunar landings by renowned space stations across the world have yielded an abundance of new scientific data on the Moon. The various experiments placed on the surface provided information on seismic, gravitational, and other lunar characteristics. But perhaps the most dramatic result of the missions was returning a total of more than 800 pounds of lunar rock and soil for analysis on Earth. These samples of the Moon offered a deeper appreciation of the evolution of our nearest planetary neighbor. 

Imagine you have been called by one of the largest space stations in the world (XYZ) space station and you are requested to make a Machine Learning model which classifies the different rocks present on the moon's surface. The purpose of this is to make the research process a lot easier. This will reduce the human effort of doing a monotonous task. There are basically two types of rocks to be classified:

Small Rocks
Large Rocks
Data:
You can find the dataset http://hck.re/kkBIfM

Data Description:
The data folder consists of 2 folders and 2 CSV files

train - Contains 5999 ‘Small Rock’ images & 5999 ‘Large Rock’ images
test  - Contains 7534 images
train.csv - 11999 x 2 (including the headers) consists of image ID and the true label for each image in the train folder
test.csv - Contains the image id for the images present in test folder for which the true label needs to be predicted
sample_submission:

Image_File,Class
clean0001.png,Large
ground0002.png,Small
ground0003.png,Small
ground0004.png,Small
Evaluation Metric:

Note: To avoid any discrepancies in the scoring, ensure all the index column ('Image_File') values in submitted file match the values in 'test.csv' provided
