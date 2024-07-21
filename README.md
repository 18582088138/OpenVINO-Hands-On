# OpenVINO-Hands-On

To ensure the consistency of the Hands-On environment, please use Linux OS. The recommended OS version:
- Ubuntu 18.04 (64-bit) with default GCC 7.5.0
- Ubuntu 20.04 (64-bit) with default GCC 9.3.0
- Red Hat Enterprise Linux 8.2 (64-bit) with default GCC 8.5.0

Software requirements
- CMake 3.13 or higher
- GCC 7.5 or higher to build OpenVINO Runtime
- Python 3.8 - 3.11 for OpenVINO Runtime Python API
- (Optional) Install Intel® Graphics Compute Runtime for OpenCL™ Driver package to enable inference on Intel integrated GPUs.

Requirement
- "openvino>=2024.0.0"
- "nncf>=2.9.0"
- torch 
- torchvision 
- tqdm

To ensure that NNCF model quantization can run smoothly, please make sure that the corresponding model and dataset in the NNCF material can be downloaded successfully. If the download fails, you can use the following link to download and upload to your device.
- datasets: http://cs231n.stanford.edu/tiny-imagenet-200.zip
- models : https://storage.openvinotoolkit.org/repositories/nncf/openvino_notebook_ckpts/304_resnet50_fp32.pth
           https://storage.openvinotoolkit.org/repositories/nncf/openvino_notebook_ckpts/302_resnet18_fp32_v1.pth

In addition, each notebook has a corresponding model file, which is not listed here one by one. 
Please make sure that the model can be downloaded successfully.