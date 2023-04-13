# Depression Level Detection using Speech Language Processing
This repository contains Colab files for the task of detecting depression levels from speech and text data.

## Overview
The notebooks in this repository are organized into several subdirectories, each corresponding to a different model or approach for detecting depression levels. The main subdirectories are:

- BiLSTM_WordLevel.ipynb: Contains a notebook implementing a BiLSTM model for depression level detection using both speech and text data.
- CNN_Audio.ipynb: Contains a notebook implementing a CNN model for depression level detection using speech data.
- CNN_Text.ipynb: Contains a notebook implementing a CNN model for depression level detection using text data.
- SVM&RF_Audio.ipynb: Contains a notebook implementing SVM and RF model for depression level detection using speech data.
- SVM&RF_Text.ipynb: Contains a notebook implementing a SVM and RF model for depression level detection using text data.
- Each notebook includes a detailed description of the methodology, data preprocessing steps, and model training and evaluation.

## Requirements
The notebooks were written in Python 3 and require several libraries to be installed, including numpy, pandas, scikit-learn, and tensorflow.

## Data
The data used in these notebooks comes from the Distress Analysis Interview Corpus (DAIC) and is included in the data directory. The data consists of audio recordings and transcripts of interviews with patients, as well as depression level scores assigned by clinical professionals.

## Conclusion
These notebooks provide an overview of several different models and approaches for detecting depression levels from speech and text data. They can serve as a starting point for further research and development of depression detection models, as well as for practical applications in clinical settings.
