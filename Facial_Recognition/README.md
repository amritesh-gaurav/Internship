## Preparing Dataset

Preparing dataset for face recognition model training.
* First we collect images of different people (celebrities, models, known figures etc.), with each individual having same number of images.
* Step 2 -  clipping their face in an image detected using face detection models
* Step 3 - Converting the image to grayscale and resizing it 64x64
* Step 4 - Converts all images to '.npy' format, creating a target numpy file to specify each individual uniquely and use it for training our model

## Final Model

Model model used for training, testing and optimisation.
