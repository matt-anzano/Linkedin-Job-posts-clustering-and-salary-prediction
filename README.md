# Linkedin Job posts clustering and salary prediction

## Description

In this project, is applied *clustering* to *LinkedIn* job posts. Initially, the job posts will be clustered using *k-means*, relying on *PCA* scores obtained after vectorizing the data using *TF-IDF* to find the most important words.

After clustering the job posts, we will conduct topic modeling on each cluster, identifying the most significant words within each cluster.

Finally, job salaries will be predicted based on the job posts where the salary is provided. Once this is achieved, we will extend the predictions to job posts where salary information is absent. The resulting salaries will be presented for each cluster obtained through kmeans

[
](https://www.kaggleusercontent.com/kf/153595165/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..Ne2sKc96Fj5H2DJEs4fp7Q.SPRo11KsRD7646VT5VHr_hAxvB3PrmL7j1G_oTrF6Ch14Y03obNSWd9uuqYRUwU5WBRNf-CLbzB-2k4znYE3yTtbIJI3abKKKBKe1HxMmL-uPI94AB0T-MMMmOTpAnDYm6zc-TTFfIuR6v7n5hATJDhgfzk6A8UQ4HyzsvZ-T8nNP-N1GhfPUweb0WzMoR2vAvRkfpSW8YEgVyeouCZYTCe-EydwnqaSU868rjVFeo8r2jXKqewK-v_GEBHOL6ueSoAdHAbL6dRzHn3auna1qOetk4lQVDx5cAgimML-yt53BzYeQvnv74FuHutgHrnqiZt94hudGeaH2eLIPe8p7DKVhguzorN8L_OkoxGnJX7THYqa-yZCmJYfEYfE9scRopaewasGxb_iqi9XdZy88J1oMG-A1zg2Dj2k1XeGImZHLzEbVyzhzIlklCmzGoBKb73zYNDxb2C62LCJlfBnf-v8c-7SCxG8H-jNGT2w_MUeC89y2VtqSQOoxJQYeNJUCPYrZr2n6ejGgftCLhK7E3Fea08umwRsY2t-Pk_QEzz6VtPq0kScK39TLQN0ZD0up6aEPfmpK6l6AQJJlXXr4Y8l-ozHA486ITrU2YT8uG2O1FwowhflWrUIqG3OHHTGxStHOQLFTQQ_ZvEm39-Q8b3_NNk0j7Mgir137sf2ZA-OVBT8kY-2aiwBfDr_OZVb.-M3_pGJ4rR-aoCwoMA73kQ/__results___files/__results___22_0.png)https://www.kaggleusercontent.com/kf/153595165/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..Ne2sKc96Fj5H2DJEs4fp7Q.SPRo11KsRD7646VT5VHr_hAxvB3PrmL7j1G_oTrF6Ch14Y03obNSWd9uuqYRUwU5WBRNf-CLbzB-2k4znYE3yTtbIJI3abKKKBKe1HxMmL-uPI94AB0T-MMMmOTpAnDYm6zc-TTFfIuR6v7n5hATJDhgfzk6A8UQ4HyzsvZ-T8nNP-N1GhfPUweb0WzMoR2vAvRkfpSW8YEgVyeouCZYTCe-EydwnqaSU868rjVFeo8r2jXKqewK-v_GEBHOL6ueSoAdHAbL6dRzHn3auna1qOetk4lQVDx5cAgimML-yt53BzYeQvnv74FuHutgHrnqiZt94hudGeaH2eLIPe8p7DKVhguzorN8L_OkoxGnJX7THYqa-yZCmJYfEYfE9scRopaewasGxb_iqi9XdZy88J1oMG-A1zg2Dj2k1XeGImZHLzEbVyzhzIlklCmzGoBKb73zYNDxb2C62LCJlfBnf-v8c-7SCxG8H-jNGT2w_MUeC89y2VtqSQOoxJQYeNJUCPYrZr2n6ejGgftCLhK7E3Fea08umwRsY2t-Pk_QEzz6VtPq0kScK39TLQN0ZD0up6aEPfmpK6l6AQJJlXXr4Y8l-ozHA486ITrU2YT8uG2O1FwowhflWrUIqG3OHHTGxStHOQLFTQQ_ZvEm39-Q8b3_NNk0j7Mgir137sf2ZA-OVBT8kY-2aiwBfDr_OZVb.-M3_pGJ4rR-aoCwoMA73kQ/__results___files/__results___22_0.png![image](https://github.com/matt-anzano/Linkedin-Job-posts-clustering-and-salary-prediction/assets/96449147/231a3a50-5dcd-4c1c-b787-81a49b8f04a2)
## Results and Output

Trough this analysis *LinkedIn* job posts are aggregated in five partialy overlapping clusters, characterized by different job roles or benefits.
Through *Random Forest*, is reached a *Relative Mean Square Error* equal to 13%, which is a good performance considering usual linkedin salary ranges. 
Moreover is analysed the salary difference in the five cluster previously obtained
