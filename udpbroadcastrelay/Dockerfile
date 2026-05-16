ARG BUILD_FROM=ghcr.io/home-assistant/aarch64-base:latest
FROM $BUILD_FROM
COPY run.sh /
RUN chmod +x /run.sh
CMD ["/run.sh"]
