# Nocturnal Glucose Risk Prediction: A Hybrid Digital Twin Approach

## Overview
This project implements a **hybrid digital twin framework** for predicting nocturnal hypoglycemia and hyperglycemia in individuals with Type 1 diabetes. By combining mechanistic physiological modeling with machine learning, the system provides **bedtime risk predictions** to enable preventive interventions before dangerous overnight glucose events occur.

## What is a Digital Twin?
A digital twin is a continuously updated computational representation of an individual's physiological state. In the context of diabetes, our digital twin models the unique glucose-insulin dynamics of each patient, enabling personalized simulation and prediction of overnight blood glucose trajectories based on their daytime patterns, meal intake, insulin administration, and historical glucose behavior.

## The Problem: Nocturnal Glucose Complications

People with Type 1 diabetes face significant overnight risks that are difficult to detect and prevent:

### Nocturnal Hypoglycemia (Low Blood Sugar)
- **Occurs in ~50% of people with Type 1 diabetes**
- Glucose levels drop below 70 mg/dL during sleep
- **Dangerous consequences**:
  - Impaired cognitive function
  - Seizures or loss of consciousness in severe cases
  - Fear of hypoglycemia leading to chronic hyperglycemia
  - Sleep disruption for patients and caregivers

### Nocturnal Hyperglycemia (High Blood Sugar)
- **Dawn Phenomenon**: Early-morning glucose elevation (4-8 AM) due to circadian hormonal changes
- **Somogyi Effect**: Rebound hyperglycemia following undetected hypoglycemia
- **Long-term complications**:
  - Vascular damage (retinopathy, nephropathy)
  - Increased cardiovascular risk
  - Chronic fatigue and reduced quality of life

### Why Nighttime is Critical
- **Limited monitoring**: Patients are asleep and cannot react to glucose changes
- **Delayed symptoms**: Warning signs go unnoticed until it's too late
- **Unpredictable dynamics**: Insulin sensitivity varies throughout the night
- **High stakes**: Severe events can occur without intervention

## Our Solution: Predictive Digital Twin System

This digital twin system functions as a **bedtime decision-support tool** that predicts nocturnal risks **before they happen**, enabling preventive action.

### How Its Intended:

```
Evening Data Collection → Digital Twin Simulation → Risk Prediction → Preventive Action
(glucose, insulin, meals)   (physiological model)   (ML classifier)   (adjust treatment)
```

### Expected data 

The data is expected to come from the OhioT1DM dataset, split into 2 different folders within the data folder: one for training and one for testing. for training it assumes _{train_dir}/{patient_id}-ws-training.xml_ and for testing it assumes _{test_dir}/{patient_id}-ws-testing.xml_. _run_analysis.py_ is the only file you have to run, after having followed the instructions in the comments at the bottom of the file.


## Contact
**Email**: l.r.merkens@student.tue.nl  
**Institution**: Eindhoven University of Technology

---

**⚠️ DISCLAIMER**: This system is designed for research and educational purposes only. All medical decisions should be made in consultation with qualified healthcare professionals. This tool does not replace continuous glucose monitoring, insulin therapy, or medical supervision.
