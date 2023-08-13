# Brain_Tumor_Detection--using-CNN
## CNN
In this project, I will build a brain tumor recognition model using CNN.
 
In this project I will use Pytorch.
+ If you use Google Colab then you don't need to install just import torch normally
+ If you use other types then need to install using command line in terminal
+ For CPU: <code>pip install torch torchvision</code>
+ For GPU(CUDA): <code>pip install torch torchvision torchaudio -f https://download.pytorch.org/whl/cu{CUDA_VERSION}/torch_stable.html</code>


Structure of the CNN network:
- An input layer (usually an image), one or more convolutional layers combined with a pooling layer, and then one or more fully connected layers to perform the final classification.
- Use convolutional and pooling layers to separate spatial information and generate low- to high-level features from the input data.
+ Use convolution to find features in spatial data (such as images).
+ Usually has less number of parameters because of shared weights in convolutional layers.

  
![R](https://github.com/Quang1129/Brain_Tumor_Detection--using-CNN/assets/72682141/d5ce62d2-9ec7-4b37-8a29-cd71dde56622)

