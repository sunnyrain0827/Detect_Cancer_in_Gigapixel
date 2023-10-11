# Detecting Cancer in Gigapixel Medical Images

## Background:
The problem we are addressing is the manual detection of cancer metastases. Metastases are secondary cancer growths that occur when cancer cells spread from the primary tumor to other parts of the body.
Because the pathology images are very high-resolution, reaching gigapixel sizes. the tumors can be relatively small. Detecting these metastases manually is not only time-consuming but also prone to human error. 
Therefore, this is where automated detection comes to the rescue. And we aim to improve the accuracy and efficiency of cancer diagnosis.

## Data Pipeline:
The data pipeline includes five steps:
1. Initial data analysis
2. Data preprocessing
3. Modeling
4. Data post processing
5. Prediction and evaluation

## Challenges:
1. Training and evaluating our models was challenging because of the large number of patches and the tumor class imbalance.
2. Another major challenge is trying to extract features that are meaningful from a clinical point of view. 


# How to use:

## Source Files and Saved Models

- Preprocessed data, SavedModels, Checkpoints: https://drive.google.com/open?id=1gWOCgU_nzW4c0HIVRuekGYUJsLDzhZOe
- Slides: https://drive.google.com/open?id=1GxeSs6jFx3lYgDsfweh2fXYW1aRu8p92
- Preprocessed Data:
  - Slide Level 4: https://drive.google.com/open?id=132rEirIq6sltBAzo62Sp7ECY5OdLXanG
  - Slide Level 5: https://drive.google.com/open?id=166wZVBnuN2ZPXprP0sYtGe1YGQjEPSge
  - Slide Level 7: https://drive.google.com/open?id=1Rz19Jju1Dm6kPKkS6ryHpgvtjfvcuEnU

## Source Codes

- 1)_Final_Initial_Data_Analysis_and_Preprocessing.ipynb: the Source code for downloading data; preprocessing data, extracting patches and labels; and saving precomputed preprocessed data to Gdrive
- 2)_Model_Pipeline_and_Evaluation.ipynb: the source code for loading precomputed data, creating model, performing predictions and drawing heatmaps
- Experiments: expeirment with different model and level
  - level4_inception_2)_Model_Pipeline_and_Evaluation.ipynb
  - level4_vgg_2)_Model_Pipeline_and_Evaluation.ipynb
  - level5_vgg_2)_Model_Pipeline_and_Evaluation.ipynb

## How to Run the code

Since the codes are run in collaboratory, make sure you have accesses to the files

## Contributions

- Deka Auliya Akbar 
- Yuting Wang 

## Youtube video
https://youtu.be/jJYXM844D5o
If you have any questions, feel free to comment.
