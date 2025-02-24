## Makeup Application Using Face Mesh and Computer Vision

This project demonstrates how to apply virtual makeup to a face image using the MediaPipe Face Mesh model and OpenCV.

### How It Works

1. Predefined Landmarks

- We use predefined facial landmarks for features like lips, cheeks, and eyelids. These points are manually specified in the code. You can find these landmarks here: [MediaPipe Face Mesh Keypoints](https://github.com/tensorflow/tfjs-models/blob/838611c02f51159afdd77469ce67f0e26b7bbb23/face-landmarks-detection/src/mediapipe-facemesh/keypoints.ts)

2. Makeup Application

- Using these landmarks, the program applies:

- Lip Color

- Blush on Cheeks

- Eyeshadow on Eyelids

3. Blending the Makeup

- The makeup effects are blended into the original image for a seamless, natural look.

### Installation

Ensure you have Python installed. Then, install dependencies:
```python
pip install opencv-python numpy mediapipe matplotlib
