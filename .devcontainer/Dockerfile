FROM mcr.microsoft.com/devcontainers/java:1-21-bullseye


RUN rm -f /etc/apt/sources.list.d/yarn.list


RUN apt-get update && \
    apt-get install -y \
    python3 \
    python3-pip \
    wget \
    unzip \
    curl \
    maven \
    libxext6 \
    libxrender1 \
    libxtst6 \
    fontconfig

RUN pip3 install notebook jupyterlab ipykernel

RUN curl -L https://github.com/SpencerPark/IJava/releases/download/v1.3.0/ijava-1.3.0.zip -o ijava.zip && \
    unzip ijava.zip -d /tmp/ijava && \
    python3 /tmp/ijava/install.py --sys-prefix && \
    rm -rf ijava.zip /tmp/ijava

EXPOSE 8888