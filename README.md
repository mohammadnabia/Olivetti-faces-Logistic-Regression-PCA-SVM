# Exploring Olivetti Faces: SVM, PCA, Covariance, and Linear Models

In this repository, we will discuss two topics. The first topic focuses on acquainting ourselves with the Olivetti Faces dataset and applying SVM with various kernels such as Linear, Polynomial (poly), Radial Basis Function (RBF), and Sigmoid kernels. Additionally, we will employ PCA for dimension reduction and retrain the SVM model.

Moving on to the second topic, we will utilize the Olivetti Faces dataset to compute the covariance matrix. Using the computed eigenvectors and eigenvalues, we will visually represent the dataset using PCA1 and PCA2. Subsequently, we will calculate Logistic Regression for our data and examine the eigenfaces. Finally, we will train our scikit-learn linear model with PCA.

## Olivetti Faces

is a widely-used dataset in the field of computer vision and machine learning. It consists of a collection of grayscale images, each depicting a face from the perspective of different individuals. The dataset was created by the Olivetti Research Laboratory and contains images of 40 distinct individuals, with each person contributing ten different facial images. These images were captured under controlled conditions, with variations in lighting, facial expressions, and poses.

The Olivetti Faces dataset serves as a benchmark for various tasks, including face recognition, facial expression analysis, and dimensionality reduction techniques. It has been utilized in numerous research studies and serves as a valuable resource for developing and evaluating algorithms in the field of computer vision.
|![download](https://github.com/mohammadnabia/Olivetti-faces-Logistic-Regression-PCA-SVM/assets/53332753/53bb3a51-79d2-4aa4-9973-56c566a21d7d) | 
|:--:| 
| *there are 40 distinct people in this data set* |

### Brief information about Olivetti Dataset:

- Face images taken between April 1992 and April 1994.
- There are ten different image of each of 40 distinct people
- There are 400 face images in the dataset
- Face images were taken at different times, variying ligthing, facial express and facial detail
- All face images have black background
- The images are gray level
- Size of each image is 64x64
- Image pixel values were scaled to [0, 1] interval
- Names of 40 people were encoded to an integer from 0 to 39

