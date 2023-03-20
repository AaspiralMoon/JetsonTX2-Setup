0. JetPack: 4.6.2
1. install openssh-server
2. Download https://developer.download.nvidia.com/compute/redist/jp/v461/pytorch/torch-1.11.0a0+17540c5+nv22.01-cp36-cp36m-linux_aarch64.whl
3. Install Pytorch: https://docs.nvidia.com/deeplearning/frameworks/install-pytorch-jetson-platform/index.html
4. Solve bugs: sudo apt-get install libomp-dev, pip3 install numpy==1.19.4
5. Install FairMOT dependencies except cython-bbox, and DCNv2

