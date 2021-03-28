ARG PYTHON_VERSION=3.8
ARG PYTORCH_VERSION=1.7

FROM pytorchlightning/pytorch_lightning:base-conda-py${PYTHON_VERSION}-torch${PYTORCH_VERSION}

RUN \
    # Show what we have
    pip --version && \
    conda info && \
    pip list


WORKDIR /opt/space/


RUN \
    python -c "import torch; assert torch.__version__== '1.7.1'"
