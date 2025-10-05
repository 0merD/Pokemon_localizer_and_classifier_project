Detailed explenation is in the python notebooks.
# Pokemon_localizer_and_classifier_project
This is an early project from late 2024 for. Final project forr a Deep Learning course at the Holon Institute of Technology.

this is a pokemon localizer and clasifier using 2 diffrent models
we used the data in this dataset to train our clasifier and as a basis of our custom dataset for localisation
https://www.kaggle.com/datasets/noodulz/pokemon-dataset-1000
first yolo as a localizer of pokemon in images. 
(its not perfect but it is an extra as the project requrments were just the clasifier)

we used transfer learning on vovod's 4 class pokemon object detector to make a general pokemon localizer with a custom version of the dataset that we manually taged 
https://github.com/vovod/yolov8-pokemon-object-detection

2nd is a custom clasifier network that cal clasify over 1000 classes of different pokemon (we used transfer learning from the base weights )

you can run any of the python notebooks the multipule versions exist only for submition purposes . 

first clone this repository

2nd. get additional resources

this is the negaupload link for the data
extract it in /data/pokemon-dataset-1000/
https://mega.nz/file/5Z0C2DoC#NMSdh7Q8GuGeucoRa6NGd6c4Rik26UJK8plgjkORfto


3. run the notebook of your choosing


these are 2 examples of usage. one using just the clasifier and a 2nd using both localizer and clasifier


<img width="640" height="368" alt="download" src="https://github.com/user-attachments/assets/a0374800-4449-48be-b69b-95e4dd1d7614" />

<img width="640" height="384" alt="download" src="https://github.com/user-attachments/assets/265ec410-0640-4551-a549-1be1a4a67524" />

<img width="1660" height="1128" alt="image" src="https://github.com/user-attachments/assets/725ac315-4e1b-4238-bf30-a98b363a3e14" />
