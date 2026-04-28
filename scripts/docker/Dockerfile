FROM ghcr.io/loong64/manylinux_2_38_loongarch64:2026.03.07-1

RUN yum install -y \
        ccache \
        ninja-build \
        && \
    yum clean all && rm -rf /var/cache/yum/*

ENV LIEF_DIR=/install/lib64/cmake/LIEF
