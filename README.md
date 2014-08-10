Scalable-Recognition-with-a-Vocabulary-Tree
===========================================

	Designed a recognition scheme, scaling efficiently to a great number of objects: extracted SIFT features for each image, and arranged these descriptors by a vocabulary tree, clustering by k-means at each level 
	Established a database with 1259 images, achieved an accuracy of 89.6% and average used time 3.2s
 A recognition scheme which scales efficiently to a great number of objects is introduced and implemented in this paper. And the good performance and high efficiency of this approach are demonstrated by the following test including a database of 259 images.
The scheme bases upon a popular technique of indexing descriptors extracted from local regions, also called SIFT feature extraction. And these local region descriptors are hierarchically quantized in a vocabulary tree, which is implemented by using K-Means clustering. The tree not only allows more discriminatory vocabulary to be used efficiently, but also integrates indexing and quantization, or allocating weights for each SIFT feature used in scoring for relevant image in the database.
The recognition is evaluated theoretically, resulting a low complexity in terms of time and space. Plus, its performance as well as robust propriety is analyzed, showing the power of the approach, explaining the influence brought by the probable noise. And the improvement of the approach are presented at last.
