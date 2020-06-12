# ComputerVisionProject
Registration plate recognition and analysis using Supervised Learning 

This project was part of 'Computer Assisted Image Analysis II' course work in my Master's program. In this project our task was to localize the license plate from the car images and recognize the registration number. Here we pre-processed the original images to remove the noise using standard image analysis concepts such as Gray-scale conversion, Image sharpening, Median and Gaussian filters to remove noises, Morphological operations to remove minute blobs and connect the edges of strong objects. Using these pre-processed images we trained an SVM model using Histogram over gradient (HOG) features. This trained model is then used to predict the license plate characters for the test images. The model resulted into an accuracy of 95.43%. 

Segmenting_using_localized_images.m contains code to preprocess the images, train the SVM model and test the images for license number recognition.

Numberplate_localisation.m contains code to localize the region of interest i.e. license plate area from the entire the car image.
