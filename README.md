# Understanding Dominance and Emotion Using the DEAP Dataset

## Overview

This project investigates the relationship between dominance, as a dimension of emotion, and other affective dimensions such as valence and arousal, using the DEAP dataset. The DEAP dataset consists of physiological and self-reported emotional responses to music videos, enabling an in-depth exploration of emotional patterns.

Conducted as part of the Data Science Club at Pasadena City College (PCC).

##### Note: Download `DEAP-understanding-dominance-and-emotion.pdf` to read the complete notebook

## Project Highlights

### Self-Assessment Analysis

We plotted visualizations of the self-assessment data and audio data including: 
- Bar charts and tables
- Amplitude Charts 
- Spectrograms
- Chromagrams

### Peripheral Physiological Data

We analyzed participant responses (self-assessment and peripheral physiological data) to a heavy metal song, identified as having the highest STD in dominance scores:
- Some participants reported high dominance (empowerment), while others reported low dominance (vulnerability) in response to the same song.
- Low dominance scores were related to stress (e.g., cooler body temperatures, slower breathing).
- High dominance scores were related to relaxation and empowerment (e.g., smiling, higher body temperatures).

### EEG Analysis and Independent Component Analysis (ICA)
- Applied ICA to EEG data from a randomly selected participant.
- Identified brain stimulations in response to a music video.

## Methodology

Exploratory Data Analysis

## How to Run

### Download the data

The EEG/Peripheral data is too large to be uploaded to Github, please download the the folder `data_preprocessed_python` from [Kaggle](https://www.kaggle.com/datasets/manh123df/deap-dataset/data) and add it to the `data` folder.

The song `Queen - I Want To Break Free.wav` has been compressed to be uploaded here. For deeper analysis of the audio please download the original.

###### Note: to learn more about all the data visit [DEAP dataset](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/readme.html)

### Run the notebook

1. Clone this repository
2. Install required dependencies using requirements.txt
3. Open in Jupyter Notebook

