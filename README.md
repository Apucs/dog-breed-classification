[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview
__A blog post regarding this to this project can be found in this [link](https://medium.com/@apu3660/dog-breed-classification-using-cnn-f94e48309e46?sk=75f7c198e55de5ad196384626e19a6ee)__

In this project, I have built a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, my algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]



## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/Apucs/dog-breed-classification.git
		cd dog-breed-classification
	```
    
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Open the notebook and follow the instructions.
	
	```
		dog_app.ipynb
	```


LICENSE: This project is licensed under the terms of the MIT license.



