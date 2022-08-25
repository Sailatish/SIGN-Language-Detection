# SIGN-Language-Detection
Which detects the sign of Deaff people and converts into text which helps the poeple to understand the lannguage and feelings of Deaff people
## Abstract:
Sign language is the preferred method of communication among the deaf and the hearing impaired people all over the world. Recognition of sign language can have varying degree of success when used in a computer vision or any other methods. Sign language is said to have a structured set of gestures in which each gesture is having a specific meaning.
## Packages used
- Tensorflow
```
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
python3 -m pip install tensorflow
# Verify install:
python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"

```
- cv2
```
pip install opencv-python
```
- numpy
```
pip install numpy
```
- object-detection
```
pip install object-detection
```
## Download TF Models Pretrained Models from Tensorflow Model Zoo
```
!cd Tensorflow && git clone https://github.com/tensorflow/models
```
