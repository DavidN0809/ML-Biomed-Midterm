# ML-Biomed-Midterm

## Train a binary classifier (called A) on the dataset using transfer learning (exactly like Assignment 1). The images should be downscaled to 128x128
The above requirement is done in the Model A notebook

## Train the SRGAN for at least 150 epochs
Next, train the SRGAN to generate 128x128 images. Each image of the training is downscaled to 32x32.
The above requirements is done in the SRGAN notebook. It was trained for 80 epochs due to running out of time.

## Show some examples of scaled images in JNB
The above requirement is done in the SRGAN notebook, and saved to the outputs folder

## Apply normalization and image transformation, and demonstrate some of the transformed samples
This is done in the Model B notebook

## Utilize the images generated by SRGAN in order to train a new model (called B)
The above requirement is done in the Model B notebook, images were generated into a ./srgan-images directory from the Generating 128x128 Images notebook.

## Compare the performance of both models using different metrics such as F1, Accuracy, AUC
This is done in the Comparison notebook.

