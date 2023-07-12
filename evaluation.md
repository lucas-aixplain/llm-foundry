# Reproducing evaluation using [llm-foundry](https://github.com/mosaicml/llm-foundry):

## Requirements:
- Docker 
- [NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html#step-1-install-nvidia-container-toolkit)
- CUDA Version 11.8 ([Instructions to install on Linux Debian 11](https://developer.nvidia.com/cuda-11-8-0-download-archive?target_os=Linux&target_arch=x86_64&Distribution=Debian&target_version=11&target_type=deb_local))

## Steps

1. Pull the following llm-foundry docker image:
```
docker pull mosaicml/llm-foundry:2.0.1_cu118-4e6a878
```
2. Run docker image:
```
docker run --gpus all -it --rm {IMAGE_ID}
```
3. Clone and install requirements from llm-foundry inside docker image:
```
git clone https://github.com/mosaicml/llm-foundry.git
cd llm-foundry
pip install -e ".[gpu]"  # or pip install -e . if no NVIDIA GPU
```
4. Run [composer](https://github.com/mosaicml/composer):
```
cd llm-foundry/scripts
composer eval/eval.py eval/yamls/hf_eval.yaml
```