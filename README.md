# geocoding-brazilian-tweets

# Geocoding Brazilian Tweets using Text Pattern Recognition

## Overview
Developed a Python-based framework to infer geographic location of Brazilian Twitter users by combining tweet metadata and text pattern recognition. The solution addresses missing or unstructured location fields and achieved over 97% positive predictive value at municipality level.


## Problem
The lack of standardized location data in Twitter profiles makes geographic analysis unreliable. This project aims to infer user location automatically from unstructured text.

## Data
The dataset consists of Brazilian tweets collected via Twitter API, including user profile metadata and tweet text. Most users had missing or noisy location fields.

## Methodology
The framework combines text normalization, regular expressions, and geographic dictionaries to detect city and state mentions in tweet text and user profiles. These signals are combined through heuristic rules to infer user location.

## Results
The approach achieved over 97% positive predictive value at municipality level when evaluated against labeled data.

## Limitations
Ambiguous city names, slang, and sarcasm remain challenges. The approach prioritizes precision over recall.

## Technologies
Python, Pandas, Regex, NLP techniques, Twitter API.

## Future Improvements
Use embeddings / transformers

Integrate interactive maps

Deploy as API

Apply to environmental or urban monitoring
