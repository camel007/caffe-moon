# caffe-moon: Face attributes predict with Mixed Objective Optimization  

## Introduction  

This repo provide a solution for face attributes prediction, I design a tiny neural network with Mixed Objective Optimizition, And trained on celebA face database with mis-aligned face.
I get 89+% accuracy, better than paper's result. The trained model is only 4+M size.  

### network structure
This network structure is inspired by [caffe-tiny](http://pjreddie.com/darknet/tiny-darknet/)
![image](https://github.com/camel007/caffe-moon/blob/master/moon_tiny.png)

## Usage  

### Train  
The script for prepare the sample will update after I clean up my code.  
1, Put this repo in "caffe-root/examples/"  
2, Modify the path in "solver" , "train_val.prototxt" and "train.sh"  
3, cd "caffe-root/"  
4, sh ./examples/caffe-moon/train.sh"  

### Test
I provide some simple python code for test.
You should install ipython befor run "test_moon_euclidean.ipynb"

## Coming soon...  
1, finetuning with 5 attributes  
2, face landmark with face attributes  
3, ...  

## Reference  

1, [MOON: A Mixed Objective Optimization Network for the Recognition of Facial Attributes](https://arxiv.org/abs/1603.07027)
