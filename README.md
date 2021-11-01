In this repo, I demonstrate how to classify images into pictures of cats or pictures of dogs by build an image classifier using `tf.keras.Sequential` model and load data using `tf.keras.preprocessing.image.ImageDataGenerator`.

## Specific concepts that will be covered:
In the process, I gain practical experience and develop intuition around the following concepts

* Building _data input pipelines_ using the `tf.keras.preprocessing.image.ImageDataGenerator` class — Takes data and label arrays or takes the path to a directory, and then generates batches of augmented data.
* Working and processing data on disk to interface with the mode.
* _Data Augmentation_ and _Dropout_ - Key techniques to tackle overfitting in computer vision tasks.

## Here is the general machine learning workflow:

1. Examine and understand data
2. Build an input pipeline
3. Build, test and train a baseline model
4. Fine-tune the model by adding Data Augmentation and Dropout to fight overfitting.
5. Test the new model with samples

![CleanShot 2021-11-01 at 23 33 06](https://user-images.githubusercontent.com/3027146/139750826-187aa2a3-e29c-4701-911e-8d201261ca6c.jpg)
