
![Screenshot (3)](https://github.com/user-attachments/assets/b0905052-36f1-43b7-bc99-7f18b6a40772)
# Outlines of Task 1 and 2:
### User-Item Matrix & k-NN Model Implementation
### User-Item Matrix Creation: Developed a matrix where rows represent users, columns represent movies, and cells contain user ratings.
### Normalization: Adjusted the matrix by subtracting each user's mean rating to standardize data.
### Finding Similar Users: Employed k-nearest neighbors (k-NN) to identify users with similar preferences.
### Score Calculation: Calculated movie scores based on the similarity of users and their ratings.
### Ranking & Prediction: Ranked movies by score and predicted ratings by adding the average user rating to the calculated score.

![Screenshot (4)](https://github.com/user-attachments/assets/22b7e1df-e334-4b2e-b0d1-e97f1b755377)



![Screenshot (5)](https://github.com/user-attachments/assets/2b255917-294a-47d4-b68c-a57ecc347492)

# Key Results:

### Optimal k value: 50, with an RMSE of 1.24.
### The k-NN model effectively captures user preferences and addresses cold start issues.
### Potential improvements include alternative similarity metrics (cosine, Jaccard) and advanced techniques (matrix factorization, deep learning).

![Screenshot (6)](https://github.com/user-attachments/assets/ad59ac48-ba2a-4c9d-9c36-e99bac801890)

![Screenshot (7)](https://github.com/user-attachments/assets/aae69d6c-953a-4374-943f-eb286d240705)
# Threshold-Based Top-N Similar Users (TTSU) Algorithm
### Description: Introduced a novel algorithm for user-based collaborative filtering, enhancing recommendation accuracy through a two-step filtering process.
### Threshold Filtering: Considered only users with a similarity above a defined threshold, improving the relevance of recommendations.
### Top-N Selection: Selected the top 'n' users from the filtered list for more accurate predictions.



![Screenshot (8)](https://github.com/user-attachments/assets/6cb21eb4-ef24-484d-a06f-5a65998ff418)


![Screenshot (9)](https://github.com/user-attachments/assets/99605441-ba11-4b94-8ce1-cc6340553a96)
# Originality & Impact:

### The TTSU algorithm's dual-filter approach offers a unique and effective solution for identifying similar users, improving the quality of recommendations compared to traditional methods like k-NN.
![Screenshot (10)](https://github.com/user-attachments/assets/54523486-9792-4873-85fe-eec951fe38ab)

![Screenshot (11)](https://github.com/user-attachments/assets/14c42540-2531-450a-908d-13bb41be0d76)

![Screenshot (12)](https://github.com/user-attachments/assets/0e6c25dd-f132-4288-9cbb-eccc28a6927f)

