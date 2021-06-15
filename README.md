# ASR REMA project - KWS using ResNet

Djesse Dirckx (s1046968)

## About
This repository contains all experiments that were conducted for the ASR REMA course. In this project, the ResNet architecture was applied to the task of keyword spotting (KWS) and evaluated in 4 different experiments. The following sections describe requirements and all files that are listed in this repository.

## Requirements
All code in this repository is written in the Python programming language. To be able to succesfully run the experiments, the following dependencies are required:
```python
h5py==2.10.0
librosa==0.8.1
matplotlib==3.3.2
notebook==6.1.4
numpy==1.19.2
pandas==1.1.3
scikit-learn==0.23.2
tensorflow==2.4.1
```
As dataset, the [Google Speech Commands Dataset was used](https://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html).

## Files
- Preprocessing:
  - [Adding noise to the audio signal](pre_processing/Noise_Addition.ipynb)
  - [Converting audio signal to MFCC feature representation](pre_processing/ResNet_preprocessing.ipynb)
- [ResNet Model](model/ResNet.ipynb). This file can be used to train the ResNet model for different configurations. The exact details are stated in the notebook file.
- Experiments. This directory contains evaluation notebooks for all conducted experiments:
  - [Experiment 1](experiments/experiment_1)
  - [Experiment 2](experiments/experiment_2)
  - [Experiment 3](experiments/experiment_3)
  - [Experiment 4](experiments/experiment_4)

**Note**: It occasionaly happens that GitHub is unable to show a notebook file in the browser. This can easily be fixed by opening the notebook locally (e.g., using Jupyter notebook)
