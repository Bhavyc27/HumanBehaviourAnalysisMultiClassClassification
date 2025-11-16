Project Overview

This project focuses on human behaviour classification using image data. The dataset consists of multiple labelled human-action images, which are processed and classified using classical machine-learning techniques. The script loads the dataset, reads all images from the specified directory, extracts Histogram of Oriented Gradients (HOG) features, handles missing or inconsistent image sizes, and prepares the final training dataset. After preprocessing, the project trains models such as Perceptron and Random Forest to classify human behaviours and evaluates them using accuracy scores.

How the Model Works

Each image is converted into a numerical feature vector using HOG descriptors, which capture the shape, structure, and motion-related characteristics present in the image. These vectors are then combined with the corresponding class labels to form a complete dataset for training. The script splits the data into training and testing sets, fits the models, computes accuracy, and prints image statistics such as number of samples per class and variation in image size. This workflow creates a reproducible pipeline for behaviour-recognition tasks without relying on deep learning models, making it lightweight and easy to run on standard hardware.
