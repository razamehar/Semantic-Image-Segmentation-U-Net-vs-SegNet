# Semantic Image Segmentation U Net vs. SegNet

## Project Overview
This project focuses on semantic image segmentation, specifically targeting images of cats and dogs. Semantic image segmentation involves classifying each pixel in an image into a specific class, allowing for detailed understanding and analysis of image contents. In this project, I  implement two popular architectures, U-Net and SegNet, for semantic segmentation and compared their performance.

## Project Inspiration
The inspiration for this project originated from François Chollet's image segmentation classifier as presented in the book "Deep Learning with Python". Expanding upon this concept, I aimed to employ architectures like to U-Net and SegNet for image segmentation, intending to compare their performance.

## Salient Features of U-Net Architecture: 
- Symmetrical architecture with equal downsampling and upsampling layers.
- Skip connections preserve spatial information.

## Salient Features of SegNet Architecture: 
- Encoder-decoder architecture.
- Uses max-pooling indices for upsampling, reducing complexity.
- Designed for efficiency, suitable for real-time and resource-constrained scenarios.

## Models' Performance
After 30 epochs, the U-Net-like architecture achieved a training loss of 0.2429 and a validation loss of 0.3614. On the other hand, the SegNet-like architecture had a training loss of 0.4011 and a validation loss of 0.4176.

## Potential Improvements
- Increase the number of images and their corresponding annotations.
- Deepen the network by adding more layers and narrow it by reducing the number of neurons.
- Introduce batch normalization layers after convolutional layers to enhance performance.

## Data Sources:
- http://www.robots.ox.ac.uk/~vgg/data/pets/data/images.tar.gz
- http://www.robots.ox.ac.uk/~vgg/data/pets/data/annotations.tar.gz

## License:
This project is licensed under the Raza Mehar License. See the LICENSE.md file for details.

## Contact:
For any questions or clarifications, please contact Raza Mehar at [raza.mehar@gmail.com].
