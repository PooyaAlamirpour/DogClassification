[//]: # (Image References)

[image1]: ./images/Labrador_retriever_06457.jpg "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"
[image4]: ./images/sample_dog_output.png "Sample Output"


## Deep Learning: Dog Classification

In this project I have implemented a Dog Classification by using the Convolutional Neural Networks (CNN). This project can be used in a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, this algorithm will identify an estimate of the canine’s breed. If supplied with an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]


## Project Instructions

### Instructions
For using this project you should clone this repository at first.
1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone git@github.com:PooyaAlamirpour/DogClassification.git
	```

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```


## (Optionally) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU.  If you'd like to use a GPU, you can spin up an instance of your own. You can use Amazon Web Services to launch an EC2 GPU instance.

The result of the project must be like below:

![Sample Output][image4]
