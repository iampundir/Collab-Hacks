# Collab-Hacks
Here are all the Hacks one need for the Google collab.

#This function is used to download the files from google collab.
CarDekho_Data_Proces.to_csv("CarDekho.csv")
files.download("CarDekho.csv")

#this fuction allows to upload the files from local machine to google collab.
from google.colab import files
uploaded=files.upload()
