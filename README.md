# predicting_genuineness_of_image

Our Goal is to predict the genuiness of image of Pavbhaji(an Indian food item) based on the metadata provided in json file.

## GIVEN :
Instagram posts data for #pavbhaji

----Dir --- dataset
                |----- images (Segregated images in "0" & "1")
                |----- Json file

Where json file consist of entries for post and its metadata.

## TASK:  
- Use the Segregated data into positive(pavbhaji)("/dataset/1") and negative (non-pavbhaji)("/dataset/0") dirs
- Build a model that could Distinguish between pavbhaji and non-pavbhaji images from ("/dataset/pavbhaji") json entry
- Attain a level of Accuracy

