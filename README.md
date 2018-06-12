# CS147-Public
Public support scripts for Brown CS147

## CUDA Script

``` bash
wget -O - -q 'https://raw.githubusercontent.com/philipxjm/CS147-Public/master/scripts/gcloud_cuda_script.sh' | sudo bash
```
## Docker Script

``` bash
wget -O - -q 'https://raw.githubusercontent.com/philipxjm/CS147-Public/master/scripts/docker_script.sh' | sudo bash
```
## Nvidia Script

``` bash
wget https://github.com/NVIDIA/nvidia-docker/releases/download/v1.0.1/nvidia-docker_1.0.1-1_amd64.deb
sudo dpkg -i nvidia-docker*.deb
```

## Python 3 Script

``` bash
wget -O - -q 'https://raw.githubusercontent.com/philipxjm/CS147-Public/master/scripts/python3_installation.sh' | sudo bash
```

## Anaconda Script

``` bash
cd /tmp
curl -O https://repo.continuum.io/archive/Anaconda3-5.2.0-Linux-x86_64.sh
bash Anaconda3-5.2.0-Linux-x86_64.sh
source ~/.bashrc
conda create --name deeplearning python=3
source activate deeplearning
conda install --name deeplearning numpy
conda install --name deeplearning matplotlib
conda install --name deeplearning tensorflow-gpu
conda install --name deeplearning keras
```
