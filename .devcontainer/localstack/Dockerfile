FROM ghcr.io/containercraft/konductor:latest

RUN set -ex \
    && sudo pip install localstack localstack[runtime] --no-cache-dir \
    && sudo rm -rf /root/.cache \
    && ${apt_clean} \
    && echo
