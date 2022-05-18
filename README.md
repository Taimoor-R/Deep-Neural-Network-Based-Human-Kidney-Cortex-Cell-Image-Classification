# Deep Neural Network Based Human Kidney Cortex Cell Image Classification

Medical image classification based on a deep neural network has helped optimise the
identification of early diseases. This is achieved via the classification of cell deformation
and their impact on organs based on their spatial organisation. In this research, we will
be classifying kidney cortex cells from an image set provided by the Broad Bioimage
Benchmark Collection(BBBC). However, medical image classification poses certain
challenges such as overfitting, data augmentation issues, and invariant class
distributions. Consequently, there are many methods and approaches to overcome
these challenges. According to research by Sahiner et al. (2018), there are various
workarounds to overfitting, including the use of regularisation, early stopping and
dropout layers[1]. Regularisers and dropout layers tend to penalise overly complex CNN
architectures by imposing an additional term to the loss function during training,
smoothing the solution and dropping units in the neural network, respectively.
The objective of this project is to classify a kidney cortex cell image set sourced through
the Broad Bioimage Benchmark Collection (BBBC) into 8 classes of different cells. The
images were taken of three deceased donor kidney nephrectomy tissues, and ”Image
acquisition was performed in four separate consecutive channels using an upright Leica
SP8 Confocal Microscope controlled by LAS X software (Germany)” (Woloshuk et al.,
2021)[5]. Moreover, according to J. Yang et al., (2021) the images have been
manipulated and resized to greyscale and image size of 28x28[6]. Furthermore, the
dataset comprises 200,000 images consisting of 150,000 images for training and 50,000
images for testing. This project aims to identify and overcome overfitting and invariant
image classes using various hyperparameters and model architecture modifications.
The methods of overcoming these issues discussed in this report will encompass
regularisation techniques, dropout layers, and data manipulation (data augmentation)
to optimise the ratio of accuracy and validation accuracy.




### References
- [1] Sahiner, Berkman et al. “Deep learning in medical imaging and radiation therapy.” Medical physics vol. 46,1 (2019): e1-e36. doi:10.1002/mp.13264
- [2] Deep Learning (Ian J. Goodfellow, Yoshua Bengio and Aaron Courville), MIT Press, 2016.
- [3] P. Thanapol, K. Lavangnananda, P. Bouvry, F. Pinel and F. Leprévost, "Reducing Overfitting and Improving Generalization in Training Convolutional Neural Network (CNN) under Limited Sample Sizes in Image Recognition," 2020 - 5th International Conference on Information Technology (InCIT), 2020, pp. 300-305, doi: 10.1109/InCIT50588.2020.9310787.
- [4] Sergey Ioffe and Christian Szegedy. Batch normalization: Accelerating deep network training by reducing internal covariate shift. In ICML, 2015.
- [5] Woloshuk, A, Khochare, S, Almulhim, AF, et al. In Situ Classification of Cell Types in Human Kidney Tissue Using 3D Nuclear
Staining. Cytometry. 2021; 99: 707– 721. https://doi.org/10.1002/cyto.a.24274
- [6] J. Yang et al. "Medmnist v2: A large-scale lightweight benchmark for 2d and 3d biomedical image classification." arXiv:2110.14795, 2021.
