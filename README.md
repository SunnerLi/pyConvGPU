# PyConvGPU

The simple example to show convolution.
</br>   
</br>    
Abstract
---------------------
This project is the entrance of the same name project that develop on Bitbucket. Since the hot topic - Deep learning use a lot computation of "convolution", so this project show a simple way to do the convolution.</br>    
The main function is develop in Python, but it do the convolution in C layer. This project use CUDA C API to enhence the speed. At last, the project would show the convolution result. This example show 4*4 image and 2*2 kernel progress.
</br>   
</br>    
Structure
---------------------
1. send the image and kernel to C function by ctypes
2. send the image and kernel to CUDA function
3. copy the image and kernel to GPU
4. convolution!
5. copy the result to memory
6. send the result to C function
7. send the result to Python function and store   

</br>   
</br>    
Code
---------------------
see [this](https://bitbucket.org/sunerli/pyconvgpu/overview)
