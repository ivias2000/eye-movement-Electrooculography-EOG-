# BioMechatronics Final Project  
![Uploading image.png…]()

This project focuses on **eye movement analysis using Electrooculography (EOG)** with KNN combined with questionnaire-based methods to assess **spatial navigation ability** and cognitive load. The goal is to design a comprehensive evaluation framework that integrates physiological signals with subjective assessments for improved accuracy and depth.  

---

##  Overview  
- **Objective**: To develop an integrated tool for assessing spatial navigation ability by combining **EOG signals** with questionnaire data.  
- **Motivation**: Traditional methods (e.g., questionnaires) provide limited insight. By integrating EOG, real-time physiological data enhances accuracy in detecting cognitive processes during navigation tasks.  
- **Applications**:  
  - Cognitive load measurement  
  - Clinical diagnosis of spatial navigation disorders  
  - Training and performance evaluation in complex environments  

---
<img width="475" height="725" alt="image" src="https://github.com/user-attachments/assets/a8afa718-84a4-41fb-b13e-bad2bca5f287" />

##  Methodology  
1. **Data Collection**  
   - Participants wore electrodes to record horizontal (A) and vertical (B) EOG signals.  
   - Eye movement tasks were performed while video stimuli were shown.  
   - Questionnaire data (demographics, spatial experience, anxiety levels, etc.) was collected.  

2. **Signal Processing**  
   - Preprocessing: detrending, noise removal, low-pass filtering, normalization.  
   - Feature Extraction (time-domain & event-based):  
     - Mean, Variance, RMS, Skewness, Peak-to-Peak, Zero-Crossing Rate  
     - Blinks, Saccades, Fixations  
<img width="487" height="408" alt="image" src="https://github.com/user-attachments/assets/930e6338-a867-41fe-8c3b-976533ef5869" />

3. **Analysis**  
   - Comparison of signal features with questionnaire results.  
   - Identification of relationships between EOG patterns, age, gender, spatial anxiety, and performance.  

---
##  Results  
- Extracted EOG features provided valuable insights into eye movement behavior during navigation tasks.  
- Clear patterns were observed in relation to **spatial anxiety, age, and navigation strategies**.  
- Integration of physiological and questionnaire data improved the reliability of cognitive load assessment.  

---

## Repository Structure  
```plaintext
.
├── data/            # Raw and preprocessed EOG signals
├── notebooks/       # Analysis and visualization notebooks
├── src/             # Signal processing and feature extraction code
├── results/         # Processed results, plots, and tables
└── README.md        # Project overview
