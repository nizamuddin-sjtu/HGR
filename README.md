# HGR: Hand-Gesture-Recognition Based Text Input Method for AR/VR Wearable Devices

## Abstract

Hand gestures, whether static or dynamic, play a crucial role in human-computer interaction, offering various applications in real-time systems. This paper introduces a hand-gesture-recognition-based text input method designed for augmented reality (AR) and virtual reality (VR) devices. The proposed system utilizes a compact architecture to achieve efficient and accurate recognition of hand gestures. The process involves capturing hand images with a standard camera, segmenting the hand using background subtraction, and inputting the segmented hand gesture into a trained neural network for recognition. Hand movements are further tracked and recorded using a convex hull algorithm, leading to the generation of corresponding written characters by a trained neural network. Experimental results demonstrate the superior performance of the proposed method, achieving an overall accuracy of 96.12%, surpassing traditional methods.

## Dataset

The dataset used in this project is available on Kaggle: [HGR Dataset](https://www.kaggle.com/datasets/nizamuddinmaitlo/hgr-dataset). It includes hand images with corresponding labels for training the neural network.

## Project Structure

- `src/`: Source code directory containing the implementation of the hand-gesture-recognition system.
- `data/`: Data directory where the dataset is stored.
- `results/`: Results directory for storing output and experimental results.

## Code Availability

The code for this project can be downloaded from Google Drive: [HGR Code](https://drive.google.com/file/d/16HSBvr9fFkdkBsxsHkWAD0VPG8iOEaT1/view?usp=sharing).

## Citation

If you use this code or dataset in your work, please cite the following paper:

```bibtex
@InProceedings{Nooruddin_2020_SMC,
    author    = {Nooruddin, N. and Dembani, R. and Maitlo, N.},
    title     = {HGR: Hand-Gesture-Recognition Based Text Input Method for AR/VR Wearable Devices},
    booktitle = {2020 IEEE International Conference on Systems, Man, and Cybernetics (SMC)},
    month     = {October},
    year      = {2020},
    pages     = {744-751},
}
