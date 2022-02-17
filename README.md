# Entity Resolution
## Familiarization with Dedupe

This notebook contains notes taken from practically going through the dedupe documentation as well as other resources to solidfy the understanding of entity resolution with active machine learning.

Reference: Gregg, Forest and Derek Eder. 2015. Dedupe. https://github.com/dedupeio/dedupe

## Overview Dedupe Library
General Overview of Dedupe Library

## Record Similarity
Additional information and study on Record Similarity algorithm, especially **Affine Gap Distance**.

## Regularized Logistic Regression and Active Learning
- Information on how Regularized Logistic Regression was used to determine whether pairs of entities were classified as "Duplicate" or "Distinct"
- Active Learning provides the feedback loop from the users to constantly "retrain" the regression model
- Predicate Blocking allows for bundle of records that share all the same features.

## Clustering Duplicates
- Dedupe uses hierarchical clustering with centroid linkage 

## Revision of Classification Metrics
- Precision and Recall
- F-score
- 
