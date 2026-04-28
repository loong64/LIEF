FROM ghcr.io/loong64/manylinux_2_38_loongarch64:2026.03.07-1

RUN yum install -y \
        ccache \
        ninja-build \
        && \
    yum clean all && rm -rf /var/cache/yum/*

WORKDIR /src
ENV LIEF_DIR=/install/lib64/cmake/LIEF
ENV PIP_EXTRA_INDEX_URL=https://gitlab.com/api/v4/projects/65746188/packages/pypi/simple
