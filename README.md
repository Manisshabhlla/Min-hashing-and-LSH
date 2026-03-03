📌Assignment: 
MinHash and LSH Implementation

📖 Overview

This assignment focuses on understanding and implementing similarity detection techniques using:

k-Grams

Jaccard Similarity

MinHash

Locality Sensitive Hashing (LSH)

The project is divided into two main parts:

Similarity analysis on small text documents (D1–D4)

Similarity detection among users in the MovieLens dataset

The goal is to study how approximate similarity methods behave compared to exact similarity computation.

🧠 Concepts Implemented
1️⃣ k-Gram Similarity

Character 2-grams

Character 3-grams

Word 2-grams

Exact Jaccard similarity computation

This part shows how similarity changes when the gram size increases.
2️⃣ MinHash

Implemented multiple hash functions

Compared estimated similarity with exact Jaccard similarity

Tested different signature sizes (t = 50, 100, 200, etc.)

This section demonstrates how increasing signature size improves approximation accuracy.
3️⃣ Locality Sensitive Hashing (LSH)

Banding technique applied

Different (b, r) configurations tested

False Positives and False Negatives analyzed

Threshold values (0.6 and 0.8) evaluated

This section highlights how LSH parameters affect accuracy and filtering performance.

📊 Key Observations

Smaller k-grams produce higher similarity values.

Larger k-grams are more restrictive and reduce similarity.

Increasing the number of hash functions reduces variance in MinHash.

LSH performance is highly sensitive to band size (r).

Proper parameter tuning significantly reduces false positives.
