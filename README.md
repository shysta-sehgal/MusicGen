# Deep Music Generation Robustness Study for Augmented Inputs

## Overview
This repository contains the research work and experimental Jupyter notebooks used in the study of data augmentation techniques on deep music generation models, done collaboratively in a team of four. Recent advances in the field have led to the development of sophisticated models capable of generating music, such as MetaAI’s MusicGen. However, questions remain regarding the robustness of these models against modified input data. Our research aims to evaluate the performance of MusicGen when exposed to various data augmentation methods.

## Data Augmentation in MusicGen
Our study introduces pitch shifting, time stretching, and volume modification to the pre-processing stage of music data to investigate the model's flexibility. By augmenting the input data systematically, we provide new insights into the model’s ability to maintain musical coherence and generate high-quality music pieces.

## Repository Contents
- `Eval_with_MFCC.ipynb`: Evaluation of MusicGen using Mel-frequency Cepstral Coefficients (MFCC) to analyze musical coherence.
- `Generate_Data.ipynb`: Scripts for generating the augmented datasets used in the experiments.
- `RMSE.ipynb`: Computation of Root Mean Squared Error (RMSE) to quantitatively assess the model's generative performance.
- `turing_data.csv`: Dataset containing human participant survey answers on Turing tests.
- `Turing_test.ipynb`: Evaluation of the data collected from the Turing tests.

## Findings
The study reveals that while MusicGen shows proficiency in generating continuations from unaltered data, its performance with augmented inputs is notably limited. The experimental results emphasize the importance of designing deep learning models for music generation that are resilient to data imperfections.

## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details.
