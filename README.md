# Dog Breed Classifier
Implementation of a dog breed classification convolutional neural network. Made for the udacity machine learning engineer capstone project.

## Implementation
The goal of this project is to build an image classification model, in which images of dogs are classified based on their breeds. If the image of a human is provided instead, it will approximate the dog breed that looks the most similar. It will be using CNNs (Convolutional Neural Networks) to achieve this purpose. For more on the idea for the implementation, and why certain models were chosen, along with a deeper explanation of the work, please read the [project report](https://github.com/davidjentjens/dog-breed-classifier/blob/main/report.pdf).

<img src="https://i.imgur.com/1WoGq8e.png"/>

## Usage Instructions
### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/deep-learning-v2-pytorch.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
    
__NOTE:__ if you are using the Udacity workspace, you *DO NOT* need to re-download the datasets in steps 2 and 3 - they can be found in the `/data` folder as noted within the workspace Jupyter notebook.

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```

__NOTE:__ While some code has already been implemented to get you started, you will need to implement additional functionality to successfully answer all of the questions included in the notebook. __Unless requested, do not modify code that has already been included.__

__NOTE:__ In the notebook, you will need to train CNNs in PyTorch.  If your CNN is taking too long to train, feel free to pursue one of the options under the section __Accelerating the Training Process__ below.

## Data

### Human Images
The human images can be obtained via [this link](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).

### Dog Images
The dog images can be obtained via [this link](http://vis-www.cs.umass.edu/lfw/lfw.tgz).
