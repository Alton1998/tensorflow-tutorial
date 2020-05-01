# Tensorflow Tutorial
## Prerequisites
* Ubuntu 18.04 WSL to install follow these steps
* Python3
* Tensorflow
* Jupyter Notebook
## WSL Installation
Open Windows Power Shell and Run the following command
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```
Go [here](https://ubuntu.com/wsl) to download thw WSL

## Python Installation

On the WSL Check if the `python3` command works if not run the following:
```bashd
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get install python3.6
python3.6
```
## Tensorflow installation

### Create a Virtual Environment

```
sudo apt install python3-venv
python3 -m venv my-project-env
```
### Activate the Virtual Environment
```
source my-project-env/bin/activate
```
### Installing Tensorflow
```
pip3 install tensorflow
```
## Install Jupyter Notebook
```
pip3 install jupyter
```
