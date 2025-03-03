# External Validation of STopTox as an Alternative to Animal Testing for Toxicological Assessments

This repository provides data and results supporting our study on evaluating the STopTox platform as a non-animal method for predicting chemical toxicity across six acute toxicity endpoints.

## Repository Structure

- **data/**  
  Contains curated datasets and source materials from the Integrated Chemical Environment (ICE).

- **results/**  
  Includes an Excel file with calculated metrics (CCR, sensitivity, specificity, PPV, NPV) for each toxicity endpoint, following the methodology described in Borba et al.
  Also contains predictions and scored using the OECD QSAR Toolbox.

## Overview

STopTox leverages QSAR models to predict toxicity for endpoints such as:
- Acute oral toxicity
- Acute dermal toxicity
- Acute inhalation toxicity
- Skin sensitization
- Skin irritation/corrosion
- Eye irritation/corrosion

External validation using independent datasets supports that STopTox can serve as a reliable alternative to animal testing, supporting regulatory efforts aligned with the principles of reducing, refining, and replacing animal use.

## Key Equations

The performance of STopTox was assessed using the following metrics:

- **Correct Classification Rate (CCR)**:
  ```math
  CCR = \frac{SE + SP}{2}
  ```

- **Sensitivity (SE)**:
  ```math
  SE = \frac{TP}{TP + FN}
  ```

- **Specificity (SP)**:
  ```math
  SP = \frac{TN}{TN + FP}
  ```

- **Positive Predictive Value (PPV)**:
  ```math
  PPV = \frac{TP}{TP + FP}
  ```

- **Negative Predictive Value (NPV)**:
  ```math
  NPV = \frac{TN}{TN + FN}
  ```

Where:
- \( TP \) = True Positives
- \( TN \) = True Negatives
- \( FP \) = False Positives
- \( FN \) = False Negatives

## References

1. Borba JVB, Alves VM, Braga RC, et al. *STopTox: An In Silico Alternative to Animal Testing for Acute Systemic and Topical Toxicity.* Environmental Health Perspectives. 2022;130(2):027012.

