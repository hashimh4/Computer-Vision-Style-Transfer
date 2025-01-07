# Computer-Vision-Style-Transfer
**Fourth Year (2023/2024) Advanced Computer Vision Module**

A sophisticated movie-game style transfer model, using state-of-the-art deep learning models and methods, with enhancements through human detection followed by human classification. 

The human detection model used was YOLO-v9, trained on the COCO person dataset. The human classification model classfied patches into baby, boy, girl, man and woman. Convolutional Vision Transformer (CVT) was used, which was adapted from Vision transformer (ViT), and trained on a subset of the CIFAR-100 dataset. 

A CycleGAN model was trained on 500-frame intervals from the training set. A further CycleGAN model was used to train specifically on detected and classified human patches, using the previous methods. These were processed frame sections were then inserted back into the original frame.

Additional detection files include humans selected from a small subset of footage from the game Mafia (2002) and the movie the Godfather (1972).

Below is a cut-scene from the game Mafia in the style of the movie the Godfather:

<img src="https://github.com/user-attachments/assets/6abd9312-c5dd-457c-8e23-d8bc44a229a2" alt="result_short" width="500" />

See a longer version [here](https://drive.google.com/file/d/1hoKzweuCDwc2wG2Np4tJ7wKyRHhhVUvg/view?usp=sharing). The full weights can be found [here](https://drive.google.com/drive/folders/1A2LgZWD75A6TSo7ewgEFHlssATi5pQkL?usp=sharing).

_Disclaimer: This work is for reference only. Copying any part of this work is prohibited._
