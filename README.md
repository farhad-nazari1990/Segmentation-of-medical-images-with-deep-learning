# Image Classification with VGG19

This project demonstrates image classification using the VGG19 model. It uses the Kvasir dataset, which contains images of gastrointestinal tract diseases. The goal is to train a model to classify these images into different disease categories.

## Prerequisites

Make sure you have the following libraries installed:

- OpenCV
- Pandas
- Matplotlib
- scikit-learn
- Keras
- TensorFlow

You can install these libraries using the following command:

pip install opencv-python pandas matplotlib scikit-learn keras tensorflow

## Dataset

The Kvasir dataset is used for training and testing the model. It consists of images categorized into different gastrointestinal diseases. The dataset can be downloaded from the following link:

[Kvasir Dataset](https://datasets.simula.no/downloads/kvasir/kvasir-dataset.zip)

Extract the downloaded dataset and update the `dataset_dir` variable in the code with the path to the extracted dataset directory.

## Usage

1. Open the Jupyter Notebook or Python IDE of your choice.
2. Run the code cell by cell in the provided code file.
3. The code will load the dataset, preprocess the images, train the VGG19 model, and evaluate its performance.
4. The accuracy and loss values will be displayed, along with a confusion matrix showing the classification results.

Feel free to modify the hyperparameters or experiment with different architectures to improve the model's performance.

## Results

The model's performance can be assessed based on the accuracy achieved and the confusion matrix generated. The accuracy indicates the percentage of correctly classified images, while the confusion matrix provides insights into the model's performance for each disease category.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
