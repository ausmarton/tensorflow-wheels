# tensorflow-wheels
A collection of tensorflow wheels compiled for fedora 28

Fedora 28 comes with CUDA 9.1 which isn't compatible with the current version of tensorflow-gpu. In order to run tensorflow-gpu, it needs to be compiled from source, which poses another challenge on Fedora 28 - i.e. it requires CUDA compilation which isn't supported by gcc 8 that comes as a default version of gcc on Fedora 28.


## Installation
```
pip install tensorflow-gpu-1.8.0-cp36-cp36m-fc28_x86_64.whl
```

## Compiled versions
### tensorflow-gpu-1.8.0-cp36-cp36m-fc28_x86_64.whl
tensorflow-gpu with CUDA 9.1, Compute capability 6.1, CudNN 7.1; compiled using gcc 7.3.0
