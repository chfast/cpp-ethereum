FROM debian:9

RUN apt -q update && \
    apt -qy install --no-install-recommends \
        git \
        ssh \
        g++ \
        cmake \
        make \
        python \
        libcurl4-openssl-dev \
        libgmp-dev \
        libleveldb-dev \
        libmicrohttpd-dev \
        libminiupnpc-dev && \
    rm -rf /var/lib/apt/lists/*

RUN apt -q update && apt -qy install ca-certificates && \
    rm -rf /var/lib/apt/lists/*
