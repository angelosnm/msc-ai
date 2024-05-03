## Project 2

### Docker setup
`docker run -d --name angelos-notebook -p9999:8888 -v ./:/home/jovyan/msc-ai --gpus all --restart unless-stopped quay.io/jupyter/pytorch-notebook:cuda12-python-3.11`

In order to run the Docker image, you must have NVIDIA Container Toolkit installed both on the host and the container runtime (https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html).
