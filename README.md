# HTR_WordSegmented

## Description

This is a Handwritten Text Extraction system based on deep learning developed using tensorflow and is trained on the IAM off-line HTR dataset. This model currently works only on images of single sentences incorporates word segmentation and allows character level accuracy of detection to better predict words outside training data.

## Getting Started

### Dependencies

* Python ver 2.7 +
* Packages Required :
editdistance
matplotlib
numpy
opencv-python
path
tensorflow

	

### Setting up the program

* Clone the repository.
* Put the image of the sentence to predict within in HTR_WordSegmented\in
* Go to the src directory
* Run the code code:
'''
python main.py
'''
* The word segmented image will be shown in HTR_WordSegmented\out
* The console will display the recognized text with accuracy rates.



## Version History

* 0.1
    * Initial Release