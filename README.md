# Internship_Case_Study_Day5

Overview

Day 5 focused on defining measurable success criteria and Key Performance Indicators (KPIs) for evaluating the proposed AI-based fraud detection system. 

Clearly defined metrics are essential to assess both technical model performance and business impact.

Why Success Metrics Are Important

Fraud detection systems must balance:
Detecting maximum fraud cases (high recall)
Minimizing false positives
Maintaining customer satisfaction
Reducing operational costs

Therefore, evaluation must consider both technical accuracy and business performance.

Technical Performance Metrics

The following machine learning metrics will be used:

Precision
Measures how many predicted fraud cases are actually fraud.

Precision = TP / (TP + FP)

Importance:
Reduces false positives
Prevents blocking legitimate transactions

Recall (Sensitivity)
Measures how many actual fraud cases are detected.

Recall = TP / (TP + FN)

Importance:
Critical for minimizing financial loss
High recall ensures fewer fraud cases go undetected

F1-Score
Harmonic mean of Precision and Recall.

Used when dataset is highly imbalanced.

ROC-AUC Score
Measures model’s ability to distinguish between fraud and non-fraud transactions across thresholds.

Target Goal:
ROC-AUC > 0.90 (for strong model performance)

Confusion Matrix Analysis
To evaluate:
True Positives
False Positives
True Negatives
False Negatives

Business KPIs

In addition to technical metrics, the following business KPIs will be considered:

Fraud Detection Rate
Percentage of total fraud successfully detected.

False Positive Rate
Percentage of legitimate transactions incorrectly flagged.

Operational Cost Reduction
Reduction in manual review workload.

Customer Experience Improvement
Reduction in unnecessary transaction declines.

Financial Loss Reduction
Decrease in fraud-related monetary loss.

Metric Trade-Off Strategy

Fraud detection involves balancing:

High Recall (catch more fraud)
vs
High Precision (avoid customer inconvenience)

The proposed system will prioritize:

High Recall  
Acceptable Precision  
Balanced F1-Score  

Baseline & Target Goals (Prototype Level)

For the prototype phase:

Recall > 85%
Precision > 80%
ROC-AUC > 0.90
Reduced false positives compared to baseline logistic regression

These values may be refined after experimentation.

Phase 1 Completion Summary

By Day 5, the following were completed:

Domain Selection  
Problem Statement  
Stakeholder Analysis  
Industry Research  
Data Requirements & Dataset Selection  
Success Metrics & KPI Definition  
