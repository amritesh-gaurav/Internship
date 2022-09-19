## Preparing Dataset

Preparing dataset for face recognition model training.
* First we collected images of different people (celebrities, models, known figures etc.), with each individual having same number of images.
* We were able to test our model on 4 different datasets - (Celebrities, Our own students dataset, Tufus and Olivetti Dataset)
* Step 2 -  clipping their face in an image detected using face detection models
* Step 3 - Converting the image to grayscale and resizing it 64x64
* Step 4 - Converts all images to '.npy' format, creating a target numpy file to specify each individual uniquely and use it for training our model

## Final Model

Model model used for training, testing and optimisation.

* The students dataset that we had did not have enough samples per individual.
* With the help of the celebrities dataset, we realise which face detection model to use(MTCNN).
* The face-clippings from Retina-Face were too short and didn't contain enough facial features.
* The model gave an accuracy of 0.79 using certain optimisation on Tufus Dataset.
* The model gave an accuracy of above 0.92 on Olivetti Dataset.
