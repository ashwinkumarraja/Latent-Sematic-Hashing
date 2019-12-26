Latent Semantic Hashing.

This is the implementation of Latent Semantic Hashing of documents , it was done as an assignment for the course of Information Retrieval.
Latent Semantic Hashing involves shingling the documents and bucketing them according to a similarity threshold.
There are three similarities used and the results are given accordingly namely Euclidean Distance , Cosine Distance and Jaccard Similarity.
The Signature Matrix is formed according to the number of hash functions selected as the number of coloumns and the distinct shingles as the rows. The matrix is broken down into b no. of bands with r no. of rows each , the function to calculate the best number of bands is included in the implementation.Thus similar documents will fall in the same bucket. Hence the particular similarity is calculated and returned.
User has to enter the document id of the document to which similar documents have to be calculated , the code returns the bucket of documents and the similar documents in order of similarity within the threshold.