This repository contains workflows developed for real-time cardiac motion tracking in stereotactic arrhythmia radioablation. The goal is to improve treatment precision by accurately modelling cardiac and respiratory motion during radiotherapy.

---

## Project Overview

Ventricular tachycardia is a life-threatening arrhythmia that is often challenging to treat safely. This project investigates a real-time tracking system for cardiac and respiratory motion during non-invasive stereotactic arrhythmia radioablation. 

## Key Components

### 1. 2D Segmentation
We develop and evaluate methods for segmenting cardiac structures (e.g., ICD lead tips) in 2D medical imaging (such as CBCT or fluoroscopy).

- Template matching methods (e.g., normalized cross-correlation)
- Deep learning approaches (e.g., Mask R-CNN)
- Evaluation using annotated ground truth data
- Accuracy assessment based on pixel-level error and detection rate

---

### 2. 2D to 3D Conversion
We reconstruct 3D motion trajectories from 2D imaging projections.

- Maximum Likelihood Estimation (MLE)-based reconstruction
- Geometric projection modelling using imaging system parameters
- Estimation of motion in LR, SI, and AP directions
- Comparison between ground truth-based and detection-based reconstructions
