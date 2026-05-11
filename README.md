# Resume Matching Engine — Redrob AI Campus Hackathon

## Overview

This project implements a Resume Matching Engine for the Redrob AI Campus Hackathon.

The system:

* Normalizes noisy resume skill data
* Constructs a shared vocabulary
* Computes TF-IDF vectors manually
* Creates binary vectors for Job Descriptions (JDs)
* Calculates cosine similarity
* Ranks the Top 3 matching candidates for each JD

The implementation uses only standard Python libraries as required in the hackathon guidelines.

---

## Features

* Skill normalization using alias mapping
* Duplicate skill removal
* Shared vocabulary generation
* Manual TF-IDF implementation
* Manual cosine similarity computation
* Candidate ranking for each Job Description
* No external ML libraries used

---

## Technologies Used

* Python
* Standard Libraries:

  * math

---

## Project Workflow

1. Skill Normalization
2. Skill Deduplication
3. Vocabulary Construction
4. TF-IDF Vector Generation
5. JD Binary Vector Creation
6. Cosine Similarity Calculation
7. Candidate Ranking

---

## Output

### JD-1 — ML Engineer

* Sneha Patel (0.57)
* Karan Mehta (0.53)
* Arjun Sharma (0.40)

### JD-2 — Backend Engineer

* Rahul Gupta (0.81)
* Ananya Krishnan (0.28)
* Deepika Rao (0.19)

### JD-3 — Frontend Engineer

* Aditya Kumar (0.67)
* Priya Nair (0.58)
* Ananya Krishnan (0.35)

---

## Hackathon Constraints Followed

* No NumPy
* No Pandas
* No Scikit-learn
* Manual TF-IDF implementation
* Manual cosine similarity implementation

---

## Author

Rahul Kumar
B.Tech IT Engineering
Maharaja Agrasen Institute of Technology
