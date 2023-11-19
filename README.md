# Adaptable-Deep-Learning-Model-for-Artistic-Style-Transfer

Artistic style transfer is a technique in computer vision and deep learning that combines the content of one image with the artistic style of another image to create a new image that merges the content and style characteristics. This process is based on neural networks and optimization techniques.

## Components Involved:
Content Image: The input image whose content features are retained in the final stylized image.
Style Image: The reference image that provides the desired artistic style to be transferred to the content image.
### Feature Extraction: 
Using a pre-trained convolutional neural network (CNN) such as VGG, features are extracted from both the content and style images at various layers.
### Loss Functions: 
Style transfer involves defining and optimizing two types of losses:
### Content Loss:
Measures the similarity between the content features of the generated image and the content image.
### Style Loss:
Measures the difference in style features between the generated image and the style image.
### Optimization: 
An optimization process minimizes the content and style losses by adjusting the pixel values of the generated image iteratively.
## Process:
### Feature Extraction:
Use a pre-trained CNN to extract content and style features from the content and style images separately.
### Define Loss Functions:
Compute content loss based on the difference in content features between the content image and the generated image.
Compute style loss based on the difference in style features between the style image and the generated image.
## Optimization:
Initialize a generated image (often the content image or a random noise image).
Update the generated image iteratively to minimize both content and style losses using gradient descent or similar optimization techniques.
Optimize to find an image that preserves the content of the content image while resembling the style of the style image.
##Output:
The final output is a stylized image that merges the content and style characteristics of the input images.
![result1](https://github.com/Ashishgirigoswami/Adaptable-Deep-Learning-Model-for-Artistic-Style-Transfer/assets/43043428/4b71f532-29e6-4104-b553-8d73f9d1a200)
![result3](https://github.com/Ashishgirigoswami/Adaptable-Deep-Learning-Model-for-Artistic-Style-Transfer/assets/43043428/0b28251b-008c-4f08-94ac-76215c26ef90)
![result2](https://github.com/Ashishgirigoswami/Adaptable-Deep-Learning-Model-for-Artistic-Style-Transfer/assets/43043428/998ea65b-9386-44b9-9d52-f432af06e77d)


## dataset link 
https://drive.google.com/file/d/1QyEJVNDpGLCYKvqcXioH_h_6d-5NTODb/view?usp=sharing
### trained model link
https://drive.google.com/file/d/1mc5KhhoAn2NwdPvQzHw6wi4yqVcSR3FI/view?usp=sharing
## requirements
PyTorch
pillow
OpenCV
