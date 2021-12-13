This project shows the difference between the preserved feature set and the original set when doing encoding in tensorflow-keras.
In the comparison part, we use UMAP (Uniform Manifold Approximation and Projection) to downscale and visualize the data. 

**Usage:**

Upload to your personal colab folder and can run directly.

**Results:**

 The following figures are the result that set N as encoded feature number:
 
1. N = 128
![image](https://github.com/JacobChen1998/comparison_of_MNIST_encoding_and_org_based_on_umap/blob/main/Figure/128.png)

2. N = 10
![image](https://github.com/JacobChen1998/comparison_of_MNIST_encoding_and_org_based_on_umap/blob/main/Figure/10.png)

3. N = 2 (plot with plt.scatter)
![image](https://github.com/JacobChen1998/comparison_of_MNIST_encoding_and_org_based_on_umap/blob/main/Figure/2_1.png)
![image](https://github.com/JacobChen1998/comparison_of_MNIST_encoding_and_org_based_on_umap/blob/main/Figure/2_2.png)

**Selecting 128,10,2 as feature number is because**:
***128*** : Feature number of SIFT.
***10*** : MNIST has 10 classes.
***2*** : See different between abrove result with UMAP and directly encode our data become 2D.
