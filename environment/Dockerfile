# hash:sha256:032d24b3766e8720b0b362b97da8643878462f6b38986e52f384392113287362
FROM registry.codeocean.com/codeocean/miniconda3:4.8.2-python3.8-ubuntu18.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install -y \
        jupyter==1.0.0 \
    && conda clean -ya

RUN pip install -U --no-cache-dir \
    matplotlib==3.4.1 \
    numpy==1.20.2
