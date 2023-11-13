# Image-Classification-DL-Project
 The classification problem is to categorize all the pixels of a digital image into one of the defined classes.

# About Image Classification Dataset
CIFAR-10 is a very popular computer vision dataset. This dataset is well studied in many types of deep learning research for object recognition.

This dataset consists of 60,000 images divided into 10 target classes, with each category containing 6000 images of shape 32X32. This dataset contains images of low resolution (32X32). 

The 10 different classes of this dataset are:

- Airplane
- Car
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck
CIFAR-10 dataset is already available in the datasets module of Keras. We do not need to download it; we can directly import it from keras.datasets.

# Short description about the model training and Tkinter gui.

Image classification on the CIFAR-10 dataset involves training a machine learning model to classify images into ten different classes: airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

Using Tkinter, a Python GUI library, you can create a user interface to interact with the model. Tkinter allows you to build windows, buttons, and other elements for user interaction.

To accelerate training with a GPU, libraries like TensorFlow or PyTorch can be utilized, which support GPU acceleration, allowing for faster model training due to the parallel processing power of GPUs.

Here's a brief overview of the process:

1. **Data Preprocessing**: Images from the CIFAR-10 dataset need to be preprocessed, including resizing, normalization.

2. **Model Building**: Create a neural network model, typically a convolutional neural network (CNN), which is well-suited for image classification tasks.

3. **Training on GPU**: Utilize GPU acceleration by configuring the deep learning library (like TensorFlow or PyTorch) to run computations on the GPU.

4. **Tkinter GUI Integration**: Using Tkinter, develop a user interface where users can interact with the trained model. This could involve functionalities such as uploading an image and getting a prediction from the model.

5. **Inference**: Use the trained model to predict the classes of images input through the GUI. Display the predictions or classification results back to the user.

Overall, this process involved  data handling, model creation, GPU-based training, GUI development, and inference for image classification on the CIFAR-10 dataset using Tkinter.
