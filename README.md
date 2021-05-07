# Movie-Recommendation--Using-KNN
Using metric = Cosine and applying cosine similarity concept


Process 
- 1. Import pandas and numpy libraries
- 2. Import  movies and ratings dataset
- 3. Merge the two datasets with column movieId
- 4. create User-Item Matrix Using pivot table with movieid as index, userId as row and ratings as values
- 5. Convert this matrix into a sparse matrix using csr_matrix for arithmetic operations and row slicing
- 6. Implement Unsupervised Machine Learning Algorith Using NearestNeighbors with metric= "cosine" and fit the model
- 7. Import the process module from fuzzwuzzy library which will speedup the searching process
-       it will extract the (movie title, the percentage of matching and its index) in the dataframe movies
- 8. The process module will  will extract the movie title, the percentage of matching and  its index in the dataframe movies
- 9. Create a function  whcih gives the cosine similarity score and finds the top n recommended movies from the sparse matrix
        
        ### NearestNeighbors.kneighbors returns the distance and indices
        - distance : Array representing the lengths to points i.e the cosine distance to the point, only present if return_distance=True, if distance is less, it is highly similiar.
       - indices :Indices of the nearest points in the matrix

![cosine](https://user-images.githubusercontent.com/70027063/117502136-b6b4e700-af9c-11eb-9d7f-e0befaaa4e47.png)
 
 
 When item1 and item2 have a smaller angle/distance --> higher similarity percentage
