# cifar10_proj
Image classification CNN in PyTorch and TensorFlow.

# description
Env: Jupyter Lab  
Note: Some code be comment out.  

###compatibility issues  
Using CUDA 11.3 and the corresponding PyTorch will encounter some Numpy errors  
when running the import syntax and getting the dataset, such as train_data[0].  
If you try to install the latest CUDA 12.8 on Windows 10, you will encounter problems because PyTorch doesn't support CUDA 12.8 yet.  
Neither in Pip or Conda package can't find a support version.  
I recommend you install CUDA 11.8, which has lots of solutions on the Internet and also supports TensorFlow.  

推荐使用 TensorFlow 2.12.0，因为这个版本已官方支持 CUDA 11.8