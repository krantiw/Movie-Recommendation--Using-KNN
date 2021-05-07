# Movie-Recommendation--Using-KNN
using metric = Cosine and applying cosine similarity concept


Process 
- 1. Import pandas and numpy libraries
- 2. Import  movies and ratings dataset
- 3. Merge the two datasets with column movieId
- 4. create User-Item Matrix Using pivot table with movieid as index, userId as row and ratings as values
- 5. Convert this matrix into a sparse matrix using csr_matrix for arithmetic operations and row slicing
- 6. Implement Unsupervised Machine Learning Algorith Using NearestNeighbors and fit the model
- 7. Import the process module from fuzzwuzzy library which will speedup the searching process
- 8. The process module will  will extract the movie title, the percentage of matching and  its index in the dataframe movies
- 9. Create a function  whcih gives the cosine similarity score and finds the top n recommended movies from the sparse matrix
