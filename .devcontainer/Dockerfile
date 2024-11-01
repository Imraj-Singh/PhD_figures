FROM pytorch/pytorch:2.3.0-cuda12.1-cudnn8-devel
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y \
    git \
    dvipng \
    texlive-latex-extra \
    texlive-fonts-recommended \
    cm-super \
    wget \
    unzip \
    && rm -rf /var/lib/apt/lists/*