# My Project Plan

**_Note_**: This document is written merely as an illustrative example and does not provide any working guide to an actual project.

### Proposal
---
I am planning to develop a computer vision software that detects objects in images. To build this application, I will utilize OpenCV, deep learning libraries such as [TensorFlow](https://www.tensorflow.org/) or [PyTorch](https://pytorch.org/), and other open-source software.

For instance, the objects in the image below were detected using [MMDetection](https://github.com/open-mmlab/mmdetection):

![Detected Objects](https://user-images.githubusercontent.com/12907710/137271636-56ba1cd2-b110-4812-8221-b4c120320aa9.png)

---
### Dependencies

- **Python**
- **OpenCV**
- **TensorFlow**
- **MMDetection**
- **Package Manager (e.g., conda)**

### Installation

In a bash terminal, run the following commands (**_Do NOT actually run these commands on your computer_**):

```bash
$ sudo apt update
$ conda create -n cv_detection python=3.8
$ conda activate cv_detection
$ python --version
$ python example.py
