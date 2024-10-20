# Building a Brain in 10 Minutes

## Overview
This project is a simple demonstration of how artificial neural networks mimic the learning capabilities of humans and animals. We walk through building a basic neural network using TensorFlow to classify articles of clothing from the Fashion MNIST dataset.

## Getting Started

### Prerequisites
To run this project, you need:
- Python 3.7+
- [TensorFlow](https://www.tensorflow.org/)
- [Matplotlib](https://matplotlib.org/)

### Running the Notebook
The `.ipynb` file is designed to run on [Google Colab](https://colab.research.google.com/). Simply upload the notebook to Colab or open it directly from your Google Drive to get started. Ensure you have a GPU runtime enabled for faster computation.

## Project Structure

1. **Introduction**
   - Explains the basics of neural networks and provides background information on their biological inspiration.
   - Includes a video excerpt from *The Machine that Changed the World*, a documentary about Artificial Intelligence.

2. **Setting Up the Environment**
   - Checks for the availability of a GPU using TensorFlow's `tf.config.list_physical_devices('GPU')`.

3. **Data Loading**
   - Uses the Fashion MNIST dataset, preloaded with TensorFlow, to train and validate the model.
   - Demonstrates the structure of training and validation datasets using Matplotlib.

4. **Building a Simple Neural Network**
   - Walkthrough of how to build and train a basic neural network using Keras' Sequential API.
   - Defines a simple architecture with a `Flatten` layer followed by a `Dense` layer of neurons.

5. **Training the Model**
   - The model is compiled with an optimizer and loss function suitable for classification tasks.
   - Trains the model over multiple epochs and validates its performance.

6. **Evaluating the Model**
   - Measures accuracy and loss during training and validation.
   - Demonstrates how to use the trained model to make predictions on new data.

7. **Conclusion**
   - Wraps up with an analysis of the model's performance.
   - Encourages further exploration into the mechanics of neural networks for those interested in improving the model's accuracy.

## Key Concepts

- **Neurons & Architecture**
  - Biological neurons are mimicked using mathematical formulas.
  - The basic structure of the model consists of 784 weights corresponding to the pixel inputs of each image.

- **Training & Validation**
  - Training data (study set) is used to help the model learn, while validation data (quiz set) checks if the model can generalize the learning.

- **Loss Function**
  - Sparse Categorical Cross-Entropy is used to evaluate the model's performance, taking into account how confident the model is in its predictions.

## Conclusion

This project demonstrates the foundational elements of building a neural network for image classification. The model achieves around 80% accuracy, showing its effectiveness but also leaving room for improvements. For those interested in diving deeper, consider exploring more advanced neural network architectures and techniques to enhance the performance.

## References

- [TensorFlow](https://www.tensorflow.org/)
- [Google Colab](https://colab.research.google.com/)
- *The Machine that Changed the World* (Documentary)
- [Fashion MNIST Dataset: Yann LeCun's Website](https://yann.lecun.com/exdb/mnist/)

## Acknowledgments

- NVIDIA for providing the inspiration and project structure.
- Google Colab for providing a platform to run and test the model efficiently.
