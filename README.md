# Install-Tensorflow-on-Ubuntu14.04

Ubuntu/Linux 64-bit, GPU enabled, Python 2.7

Requires CUDA toolkit 8.0 and CuDNN v5. For other versions, see "Installing from sources" below.

export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/gpu/tensorflow_gpu-1.0.1-cp27-none-linux_x86_64.whl

sudo pip install --upgrade $TF_BINARY_URL
