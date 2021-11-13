This repository demonstrates how to classify images into pictures of cats or dogs by building an image classifier using `tf.keras.Sequential` model.

## There are some concepts covered in this project:
* Taking data and label arrays or takes the path to a directory, then generates batches of augmented data by building _data input pipelines_ with the support of `tf.keras.preprocessing.image.ImageDataGenerator` class.
* Working and processing data on disk to interface with the model.
* Tackling an overfitting problem in computer vision by implementing _Data Augmentation_ and _Dropout_  techniques.
* Using a Transfer Learning (MobileNet) to improve the model's performance (over 97% accuracy).

## Here is the general machine learning workflow:

1. Examine and understand data.
2. Build an input pipeline.
3. Build, test and train a baseline model. As we can see, **overfitting** occurs when the model achieve a good fit on the training data, while it does not generalize well on new, unseen data. 
<p align="center"><img src="https://user-images.githubusercontent.com/3027146/141526050-9f53d7e6-c9e8-4968-86e8-81b155b3c964.jpg" width="400"></p>
4. Fine-tune the model by adding Data Augmentation and Dropout to prevent overfitting. There is an improvement in the model's performance, <b>from 60% to approximately 80%</b>.
<p align="center"><img src="https://user-images.githubusercontent.com/3027146/141526073-3a0442a9-e6e8-441f-8664-e668bf2eb51b.jpg" width="400"></p>
5. Reusing the MobileNet model to increase the model's performance to <b>over 95%</b>.
<p align="center"><img src="https://user-images.githubusercontent.com/3027146/141526591-0efefcbd-b81d-428c-aaa0-71001c4a767a.jpg" width="400"></p>
6. Running the prediction on some sample images.
<p align="center"><img src="https://user-images.githubusercontent.com/3027146/141527098-423b0457-e98f-4433-81f0-dc19c47d83b1.jpg" width="800"></p>
