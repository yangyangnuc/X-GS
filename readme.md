# 1 Introduction
## what can X-GS do?
- static street and rigid object 3D modeling using 3D Gaussians
- dynamic rigid object 3d gaussian modeling
- non-rigid person 3d gaussian modeling
- fine details single object 3d gaussian modeling

# 2 Installation
using miniconda, ubuntu 22, create virtual environment.
```bash
conda create -n x-gs python=3.8
```


Install gpu version pytorch  
```
pip install torch==2.1.2+cu118 torchvision==0.16.2+cu118 --extra-index-url https://download.pytorch.org/whl/cu118
```


Install CUDA
```
conda install -c "nvidia/label/cuda-11.8.0" cuda-toolkit
```

Install cuDNN (tiny and open source version)
```
pip install ninja git+https://github.com/NVlabs/tiny-cuda-nn/#subdirectory=bindings/torch
```