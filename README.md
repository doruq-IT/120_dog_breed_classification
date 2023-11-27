# 120_dog_breed_classification

## Advanced Dog Breed Classifier: Leveraging Deep Learning with ResNet50V2
Dive into the fascinating world of canine genetics with our cutting-edge Dog Breed Classifier! This repository presents a meticulously crafted project that harnesses the power of deep learning to accurately identify dog breeds from images. Built upon the robust architecture of ResNet50V2 and enhanced with innovative data augmentation techniques, our model achieves remarkable accuracy in distinguishing between a wide array of breeds.

## Key features of this project include:

Utilization of the ResNet50V2 model for high-level feature extraction.
Implementation of dynamic data augmentation to enrich the training dataset and enhance model robustness.
Strategic application of regularization techniques to combat overfitting.
Fine-tuning of hyperparameters using advanced techniques like Keras Tuner for optimal performance.
Comprehensive analysis and visualization of model training metrics.
Whether you're a dog enthusiast, a seasoned data scientist, or someone intrigued by the capabilities of AI, this repository offers valuable insights and a solid framework for developing sophisticated image classification models. Join us in exploring the intersection of technology and biology, and see how deep learning is reshaping our understanding of man's best friend!

## Getting Started
Follow these instructions to get the project up and running on your local machine for development and testing purposes.

## Prerequisites
Before you begin, ensure you have met the following requirements:

Python 3.6+: You'll need Python installed on your machine. Download Python.
TensorFlow 2.x: This project uses TensorFlow for deep learning. See TensorFlow's installation guide.
Keras: Required for building and training the neural network models. It's included with TensorFlow 2.x.
Other Python Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, keras-tuner. These can be installed via pip.
To check if you have Python installed, run this command in your terminal:
- python --version

## Installing
To install this project, follow these steps:
### 1- Clone the repository:
  git clone https://github.com/doruq-IT/120_dog_breed_classification.git
  cd 120_dog_breed_classification

### 2- Set up a virtual environment (optional but recommended):
  On Windows:
    python -m venv venv
    .\venv\Scripts\activate
  On MacOS/Linux:
    python -m venv venv
    source venv/bin/activate

### 3- Install the required packages:
  pip install -r requirements.txt

## Usage
To use this dog breed classifier, follow these steps:

### 1- Prepare your dataset:
Place your dog images in the data/images folder (You'll need to create this directory in the project root).

### 2- Train the model:
Run the training script with:
  python train.py
  
### 3- Classify dog breeds:
Once the model is trained, use it to classify dog breeds with:
  python classify.py --image path/to/dog/image.jpg
  Replace path/to/dog/image.jpg with the path to the dog image you want to classify.

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## Authors
Okan - Data Scientist - doruq-IT

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.



