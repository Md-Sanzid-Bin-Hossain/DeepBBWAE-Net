# DeepBBWAE-Net: A CNN-RNN Based Deep SuperLearner For Estimating Lower Extremity Sagittal Plane Joint Kinematics Using Shoe-Mounted IMU Sensors In Daily Living
By Md Sanzid Bin Hossain, Joseph Dranetz, Hwan Choi, Zhishan Guo

## Overview

This repository contains the implementation of a novel framework, **DeepBBWAE-Net**, for estimating joint kinematics using a reduced number of Inertial Measurement Unit (IMU) sensors. The framework leverages advanced deep learning techniques to predict hip, knee, and ankle angles in the sagittal plane using only two shoe-mounted IMU sensors. The proposed method has been tested across various practical walking conditions, including treadmill, overground, stair, and slope environments.

## Highlights

- **Reduced Sensor Setup**: Only two shoe-mounted IMU sensors are used to estimate joint kinematics, reducing the complexity and cost of data collection.
- **Multiple Walking Conditions**: The model has been evaluated on treadmill, overground, stair, and slope walking conditions, making it robust across different real-world environments.
- **Deep Learning Models**: Five baseline models based on Convolutional Neural Networks (CNN) and Gated Recurrent Units (GRU) were developed to predict joint angles.
- **Novel Framework - DeepBBWAE-Net**: 
  - Ensemble techniques such as bagging, boosting, and weighted averaging are used to improve prediction accuracy.
  - Outperforms the baseline models by 6.93-29.0% in Root Mean Square Error (RMSE) for joint angle predictions.

## Key Features

- **DeepBBWAE-Net**: The ensemble learning framework combines the power of multiple base models for improved prediction of joint kinematics.
- **Base Learners**: The framework employs CNN and GRU-based Recurrent Neural Networks (RNN) as base models to capture temporal and spatial features from IMU sensor data.
- **Improved Accuracy**: The novel framework achieves significant improvements in kinematic prediction accuracy compared to individual models.

## Results

- Achieves a **6.93-29.0% RMSE improvement** over the baseline models in predicting joint angles.
- First study to use a reduced number of IMU sensors to estimate joint kinematics in various walking environments.


## Data
- Data can be accessed with the following Google Drive [Link](https://drive.google.com/drive/folders/17uM_eZ8sstzeKAWtlEkhg06HDrRYaPCR?usp=sharing)

## Citations
If you use dataset or code of the paper, please cite the following paper.

``` bibtex

@article{hossain2022deepbbwae,
  title={Deepbbwae-net: A cnn-rnn based deep superlearner for estimating lower extremity sagittal plane joint kinematics using shoe-mounted imu sensors in daily living},
  author={Hossain, Md Sanzid Bin and Dranetz, Joseph and Choi, Hwan and Guo, Zhishan},
  journal={IEEE Journal of Biomedical and Health Informatics},
  volume={26},
  number={8},
  pages={3906--3917},
  year={2022},
  publisher={IEEE}
}

