# Face-Verification
Face Verification using Siamese Neural Network

This project implements a Siamese Neural Network (SNN) for face verification, designed to determine whether two input facial images belong to the same person. The network architecture is built using Convolutional Neural Networks (CNNs) to extract key facial features and compare them effectively. By taking three sets of images—anchor, positive, and negative—the network learns to minimize the distance between similar images (anchor and positive) while maximizing the distance between dissimilar ones (anchor and negative). The model is trained using a binary cross-entropy loss function and optimized with the Adam optimizer.

Throughout the training, batches of 16 images are processed, and the F1 score is used as the evaluation metric to ensure balanced precision and recall. The technology stack includes Keras with a TensorFlow backend, along with OpenCV and NumPy for image preprocessing. The project is compatible with CPU and GPU-based training, making it scalable for various hardware configurations. To use the project, install the necessary dependencies and run the training script. The model holds potential for applications like face authentication in security systems, identity verification, and attendance tracking, with future expansions possible to improve accuracy and handle larger datasets.

