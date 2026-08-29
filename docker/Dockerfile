FROM ubuntu:24.04

RUN apt-get update && \
    apt-get install -y \
    g++ \
    cmake \
    git \
    && rm -rf /var/lib/apt/lists/

WORKDIR /app

CMD ["bash"]