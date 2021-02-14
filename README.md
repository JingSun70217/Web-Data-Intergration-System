


# Web Data Integration System 


Integrating music data from different websites in different formats into one dataset.


# Phase I: Data Collection, Schema Mapping, and Data Translation

 1. Collect data from the Web. 
 2. Generate integrated schema (target schema) using XML. 
 3. Convert all data into the integrated schema using MapForce.


Result: All data is represented using a single unified schema


# Phase II: Identity Resolution

 1. Identify records in different data sets that describe the same entity.
 2. Experiment with different combinations of similarity measures.
 3. Use blocking to speed up the comparisons.
 4. Evaluate quality of your approach.

Result: Correspondences between records in different data sets that describe the same entity.

# Phase III: Data Fusion

 1. Merge data and resolve data conflicts.
 2. Experiment with different conflict resolution strategies.
 3. Measure the quality and completeness of the final fused data set.

Results: Fused data set in which each real-world entity is described by only a single record and these records contain no data conflict.


