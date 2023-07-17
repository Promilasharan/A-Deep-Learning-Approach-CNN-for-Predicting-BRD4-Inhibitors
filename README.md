# A-Deep-Learning-Approach-CNN-for-Predicting-BRD4-Inhibitors
- Bromodomain-containing protein 4 (BRD4) is a protein that plays a crucial role in epigenetic regulation and chromatin remodeling. It belongs to the bromodomain and extraterminal domain (BET) family of proteins, which are involved in reading and interpreting the epigenetic marks on chromatin.
- BRD4 contains two N-terminal bromodomains, which are protein domains that specifically recognize and bind to acetylated lysine residues on histone proteins. Histone acetylation is a post-translational modification that relaxes the chromatin structure, making the underlying DNA more accessible to transcription factors and the transcriptional machinery. By binding to acetylated histones, BRD4 helps facilitate the recruitment of various transcriptional regulators to the chromatin, influencing gene expression and cellular processes.
- Due to its crucial role in gene regulation, BRD4 has been implicated in various cellular processes, including cell cycle regulation, cell growth, and differentiation. Additionally, BRD4 is often associated with cancer development and progression, making it an important target for cancer research and drug discovery.
- Researchers and pharmaceutical companies have been exploring inhibitors targeting BRD4 as potential treatments for cancer and other diseases. By inhibiting BRD4's bromodomain interactions, it may be possible to selectively disrupt gene transcription and halt cancer cell growth, leading to promising therapeutic strategies in oncology.
- Understanding the functions and mechanisms of BRD4 has opened up new avenues of research in the fields of epigenetics and cancer biology, making it a critical protein in both basic science and translational medicine.
# A Deep Learning Approach (CNN) for Predicting BRD4 Inhibitors


## Overview

This repository contains a deep learning project focused on predicting inhibitors of the Bromo-domain containing 4 (BRD4) protein using Convolutional Neural Networks (CNN) and molecular fingerprints. BRD4 is a key epigenetic regulator, and identifying potential inhibitors can have significant implications in drug discovery and medical research.

The project utilizes a dataset obtained from the ChEMBL database, comprising chemical compounds and their respective interactions with BRD4. Data preprocessing includes exploratory analysis, handling missing values, and generating molecular fingerprints to prepare the dataset for CNN model training.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Data Preprocessing](#data-preprocessing)
- [Model Development](#model-development)
- [Model Training](#model-training)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to build a deep learning model, specifically a Convolutional Neural Network (CNN), to predict potential BRD4 inhibitors. BRD4 is a protein involved in epigenetic regulation, and the identification of inhibitors can have significant implications in drug discovery and medical research.

## Dataset

The dataset used in this project was obtained from the ChEMBL database (https://www.ebi.ac.uk/chembl/). ChEMBL is a large database containing bioactivity data for small molecules, including information on their interactions with proteins, enzymes, and other targets.

### Data Description

The ChEMBL dataset used in this project contains chemical compounds and their respective interactions with the Bromo-domain containing 4 (BRD4) protein. The data includes molecular structures, compound IDs, assay IDs, and measured activity values (potency, IC50, or Ki) that represent the inhibitory effects of the compounds on BRD4.

Due to licensing and copyright restrictions, we cannot provide the raw data in this repository. However, you can access the ChEMBL database (version X.X.X) to obtain the data used in this project. The data can be downloaded in various formats, such as CSV or SDF, and can be filtered to extract the specific data relevant to the BRD4 interactions.

### Data Preprocessing

Before training the CNN model, the raw data from ChEMBL underwent several preprocessing steps to remove duplicates, handle missing values, and extract molecular fingerprints for use in the deep learning model. Details of the data preprocessing can be found in the Jupyter Notebooks under the "notebooks" directory.

Please note that due to data privacy and licensing restrictions, the dataset used in this project may differ from the original ChEMBL data, as it was modified to ensure compliance with usage terms and conditions.

## Installation

To run the code in this project, you need the following dependencies:

- Python (>=3.6)
- Jupyter Notebook
- TensorFlow (>=2.0)
- RDKit
- Scikit-learn
- Pandas
- Numpy

