Building Segmentation Using Deep SegNet
This project implements a semantic segmentation model to detect and segment buildings from satellite images using a custom-built Deep SegNet. The dataset comprises RGB images and corresponding binary masks.

Features
Data Preprocessing:

Converts TIFF images into numpy arrays.
Applies data augmentation using TensorFlow's ImageDataGenerator.
Model Architecture:

Custom Deep SegNet architecture with Batch Normalization, Dropout, and Skip Connections.
Encoder-Decoder structure with Convolution, MaxPooling, and Transposed Convolution layers.
Training:

Optimized with Adam optimizer and Binary Cross-Entropy loss.
Early stopping mechanism to prevent overfitting.
Evaluation:

Predicts binary masks for test data.
Visualizes predictions compared to ground truth masks.

Dependencies
TensorFlow 2.x
NumPy
Matplotlib
Pillow
glob
Google Colab (for drive access)

Results
The model segments building structures from satellite imagery and visualizes predictions compared to the actual ground truth. Example results include binary masks for input images.

Future Work
Fine-tuning hyperparameters for higher accuracy.
Adding more data augmentation techniques.
Implementing advanced architectures like U-Net or Mask R-CNN for comparison.
