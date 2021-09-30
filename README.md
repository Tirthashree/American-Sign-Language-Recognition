# American-Sign-Language-Recognition
The MNIST sign language dataset contains image data for the letters of English alphabet, excluding the letters 'j' and 'z' as they require hand movement.\
The dataset is normalised.\
A convolution neural network model is compiled and trained. But the model does not seem to generalise perfectly.\
To increase the validation accuracy, data augmentation is performed. In this step, images are randomly rotated, zoomed, shifted, and flipped.\
A convolution neural network model is compiled and trained with the augmented data as well, and achieves an accuracy of 94.94%.
