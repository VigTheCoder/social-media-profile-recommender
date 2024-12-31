# Scoial Media Profile Recommender

## Description
This project implements a profile matching algorithm that calculates similarity scores between different profiles based on key attributes like professional background, interests, and personal information. By using well-known similarity metrics, profiles with a high degree of similarity are recommended for further action, such as social media connections or job matches.

## Features
- Calculates profile similarity using Cosine Similarity and Jaccard Index.
- Evaluates profiles based on professional, interest, and personal attributes.
- Recommends profiles that meet a predefined similarity threshold.
- Ideal for applications like social media platforms and job recommendation systems.

## How It Works
The algorithm compares profiles based on attributes such as education, occupation, hobbies, city, and more. Similarity scores are calculated for each attribute using appropriate similarity metrics. Cosine Similarity is applied to non-numeric attributes (like hobbies, occupation), while Jaccard Index is used for numeric attributes (like age, city). Once similarity scores are computed for each attribute, an overall similarity score is calculated for each profile. Profiles with a similarity score above the predefined threshold are considered a match and recommended.

