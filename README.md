# CS224n_project

Installed packages on the project virtualenv (all just pip install on linux):  
numpy  
tensorflow  
Cython (for the COCO PythonAPI)  
matplotlib (not yet used)  
sklearn (not yet used)  
scipy (not yet used)  
pandas (not yet used)  

********  

Clone the Tensorflow models repo: https://github.com/tensorflow/models  

Download the Inception-V3 model to where you want it (in my case to ~/CS224n/Project/CS224n_project/inception):  
$ cd models/tutorials/image/imagenet  
$ python classify_image.py --model_dir ~/CS224n/Project/CS224n_project/inception 

How to extract features from the second-to-last layer of the pretrained CNN:  
https://www.kernix.com/blog/image-classification-with-a-pre-trained-deep-neural-network_p11  

******   

Dataset: Microsoft COCO:  
http://mscoco.org/dataset/#download  

Clone/download and place the "coco" folder in your project directory:  
https://github.com/pdollar/coco  

Download the images and place in:  
coco/images  

Download the annotations and place in:  
coco/annotations  

To install the Python API:  
$ cd coco/PythonAPI  
$ make  

