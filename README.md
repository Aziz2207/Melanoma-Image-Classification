# Melanoma-Image-Classification
Developed a deep learning project for binary classification of skin lesions into benign and malignant categories to assist in melanoma detection. The project leverages a Convolutional Neural Network (CNN) for high-accuracy classification.

Key Features:

- Dataset: Used the Melanoma Skin Cancer Dataset of 10,000 Images from Kaggle for training and validation (Link : https://www.kaggle.com/datasets/hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images/data).
- Data Preprocessing: Automated loading, augmentation (random flips, rotations, and zooms), and preprocessing of skin lesion images to improve model generalization.
- Model Architecture: Designed and implemented a CNN with batch normalization and dropout layers to enhance stability and prevent overfitting.
- Training and Evaluation: Used TensorFlow/Keras for model training and validation, plotted learning curves, and evaluated performance using confusion matrices and classification reports.
- Visualization: Displayed predictions, confusion matrix (normalized and non-normalized), and performance metrics through detailed plots.
Technologies Used:

- Python for scripting and implementation.
- TensorFlow/Keras for building and training the CNN model.
- Matplotlib for visualizations.
- Scikit-learn for generating classification reports and confusion matrices.
- PIL (Pillow) for handling image data.
