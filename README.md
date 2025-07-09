# Recipe_Data
Identifying key entities in recipe data
## Problem Statement
The goal was to build a Named Entity Recognition (NER) model capable of parsing unstructured
recipe ingredient text and identifying three key entities: ingredients, quantities, and units. This
structured output is essential for powering advanced features in modern applications, such as
recipe management systems, dietary trackers, and e-commerce platforms, by making recipe
data machine-readable and easy to analyze

Insights:
-  Data Consistency: The EDA revealed that the data distribution was similar
across the training and validation splits, confirming a representative partition.
However, it also exposed quality issues, such as inconsistent labeling of singular
vs. plural units ("cup" vs "cups") and the tagging of descriptive words ("chopped")
as ingredients.
-  Model Performance: The model achieved high F1-scores across all categories
on the validation set, demonstrating that it generalized well from the training data.
Error analysis showed that most mistakes occurred in ambiguous contexts,
where a word could plausibly belong to multiple categories without stronger
contextual clues

