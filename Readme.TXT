Readme file

CS-4263-001-Spring-2021-Deep Learning

How to run:
THIS IS MEANT TO BE RUN ON GOOGLECOLLAB

Have the Musical_Genre_Deep_Learner.ipynb and the Data_Images folder
in one place. If you are running this is a Shared Drive...

Right click the "Data_Image/images_original" folder, select "Add Shortcut to drive"
and then select "My Drive". This will create a reference to the folder in your drive
in order to access the image files.

Swap the runtime type to either GPU or TPU, everything will run top to bottom.
If you recieve a error on the image loading, then the location or path of the images
isn't in the correct place in your google drive.

The run will create a logs folder in your google drive you can access and read from.


What the Project does:

This project learns and deciphers spectrogram data of various musical genres located
in the Data_Images folder. Feeding data through a U-Net model, it accurately validates
what spectrogram belong to which genre of music. 


Dataset:
GTZAN, spectrograph data sourced from Kaggle and using a ResNet to learn audio features


Code Overview and Organization:

We create a table of contents to jump to key points of our code. Starting with the Description
of what our project actually is, we follow into any notices that you would need to know if you 
are running it for the first time (this is also detailed in "How To Run" of the Readme).

Each cell is responsible for its own job. Import cell has the all the import statements for the
project preceeded by a Table Of Contents keypoint. We follow this idea to each code cell in the
project. Code is commented and each cell is Titled with a description of what each cell is 
responsible for and does.

Version:
no version requirements, we are using the latest version of Tensorflow in Python. 