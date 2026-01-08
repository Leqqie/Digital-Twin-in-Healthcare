# Diabetes Digital Twin: Nocturnal Glucose Risk Prediction

## Overview

This project implements a **hybrid digital twin framework** for personalized diabetes management, with a specific focus on predicting and preventing nocturnal glucose complications. By combining mechanistic physiological modeling with machine learning, the system provides night-level decision support to help individuals with Type 1 diabetes avoid dangerous overnight blood glucose events.

## What is a Digital Twin?

A digital twin is a continuously updated computational representation of an individual's physiological state. In the context of diabetes, our digital twin models the unique glucose-insulin dynamics of each patient, enabling real-time simulation and prediction of blood glucose trajectories under various conditions such as meals, insulin administration, and physical activity.

## The Problem

People with diabetes face significant overnight risks:

- **Somogyi Effect**: Rebound hyperglycemia (high blood sugar) following nocturnal hypoglycemia (low blood sugar), triggered by counter-regulatory hormonal responses
- **Dawn Phenomenon**: Early-morning glucose elevation due to circadian changes in insulin sensitivity

These nocturnal disturbances can lead to:
- Short-term complications (fatigue, excessive thirst, acute metabolic issues)
- Long-term vascular and neurological damage
- Reduced quality of life and increased disease burden

## Our Solution

This digital twin system functions as a **night-level decision-support tool** that:

1. **Personalizes to each patient** by learning from their historical continuous glucose monitoring (CGM), insulin, and meal data
2. **Simulates overnight glucose dynamics** using mechanistic physiological models with individualized parameters
3. **Predicts nocturnal risks** through a hybrid approach combining:
   - Mechanistic glucose-insulin modeling (interpretable, physiologically grounded)
   - Machine learning refinement (XGBoost classifier capturing complex patterns)
4. **Provides early warnings** before bedtime about potential overnight hypoglycemia or hyperglycemia

## Clinical Impact

By predicting nocturnal glucose complications before they occur, this system enables:

- **Proactive intervention**: Adjust evening insulin doses or bedtime snacks
- **Improved safety**: Reduce dangerous hypoglycemic events during sleep
- **Better glycemic control**: Prevent morning hyperglycemia and improve overall glucose stability
- **Enhanced quality of life**: Reduce anxiety and improve sleep quality for patients and caregivers


## Getting Started

There is a README file available in both model folders with instructions on how to run the code


## Contact

Outlook @l.r.merkens@student.tue.nl

**Note**: This system is designed for research purposes. Clinical decisions should always be made in consultation with qualified healthcare professionals.
