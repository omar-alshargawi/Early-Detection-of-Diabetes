🔍 Diabetes Risk Stratification: Making AI Work Smarter for Early Detection
The Challenge
Diabetes isn't just "yes or no" - people fall into different risk levels. Traditional binary classifiers fail to capture this spectrum, missing critical opportunities for early intervention. Many patients progress through early stages undetected because existing models don't provide actionable risk stratification.

✨ Our Solution
We developed a 3-tier risk classification system that upgrades standard approaches:

🔴 High Risk (needs immediate attention)

🟡 Medium Risk (requires monitoring)

🟢 Low Risk (routine checks)
1. Model Performance Comparison
   
   ![1749408785587](https://github.com/user-attachments/assets/f3db5eb9-a7ca-4f07-9fff-74483564ee79)

Supervised Learning Showdown

Random Forest dominated (F1: 0.975, AUC: 0.997)

Our enhanced 3-class Logistic Regression achieved 92% accuracy

2. ELBO Convergence
  
   ![1749408786404](https://github.com/user-attachments/assets/1f62df15-ac81-4672-84a0-4f9315c1f2c7)
   
3.Silhouette Validation

![1749408785908](https://github.com/user-attachments/assets/b354011a-078b-41a8-a958-d197251c66c3)

k=3 optimal (score: 0.4338) for risk tiers

4. PCA + KMeans Clustering

![1749408786714](https://github.com/user-attachments/assets/c8c4c4e3-fb27-4954-a313-972418df96e9)

5. Age-BMI Risk Patterns

![1749408786947](https://github.com/user-attachments/assets/4582f54b-d424-48ad-81fe-7fb269bc0589)

6. Hierarchical Clustering

![1749408786338](https://github.com/user-attachments/assets/fec91c4b-1b99-454b-aa32-db83c9045e62)

Alternative Validation

Natural groupings confirm risk tiers

Robust across 25,000 samples

7. Probability Thresholding

![1749408787605](https://github.com/user-attachments/assets/047f92ac-f09d-45c0-ab07-5bb3198a2eea)

Precision Medicine

Custom thresholds:

0.33 >= Low Risk

0.33-0.66 = Medium

0.66 < High

8. Confusion Matrices
   
![1749408786548](https://github.com/user-attachments/assets/7abc3adc-c0e0-4036-b955-e70e34a81a0b)
