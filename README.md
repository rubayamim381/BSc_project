# Document Similarity Measure with Locality Sensitive Hashing
When we discuss similar documents, we generally refer to documents that are semantically related, 
like two news articles about the same occurrence. The semantic relatedness of documents can be 
determined in a variety of methods. However, among them, **Locality sensitive hashing (LSH)** is 
a faster application that utilizes hashing values to find comparable documents from big datasets in 
a matter of seconds. 

* It refers to a set of functions (known as LSH families) that hash data points into buckets in such a way that data points close together are likely to be in the same bucket, while data points far apart are likely to be in distinct buckets. 
* This makes identifying various degrees of resemblance much easy. 

In Document Similarity Measure with LSH, we discussed a way of making that process computationally feasible between **Jaccard similarities** to **Min-hash process** in Locality Sensitive Hashing technique. 

It will proceed in a less consuming time. We need to conduct 𝑛 × (n − 1)/2 comparisons for a collection of n documents, which is practically O(n2) in brute-force method but the LSH method attempts to reduce this down to O(N) time.
