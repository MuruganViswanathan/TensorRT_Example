# TensorRT_Example

Instructions: https://docs.nvidia.com/deeplearning/tensorrt/quick-start-guide/index.html#ex-deploy-onnx


Install TensorRT in conda env (we need python3):

   python -m pip install --upgrade pip
   python -m pip install wheel
   python -m pip install --upgrade tensorrt

Verify installation:

> python
Python 3.9.20 (main, Oct  3 2024, 07:38:01) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> import tensorrt
>>> print(tensorrt.__version__)
10.6.0.post1
>>>
>>> assert tensorrt.Builder(tensorrt.Logger())
>>>