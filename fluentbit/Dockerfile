FROM fluent/fluent-bit:3.2.6
ENV DEBIAN_FRONTEND noninteractive
# RUN cmake -DFLB_CONFIG_YAML=Off ../
WORKDIR /fb
COPY ./fluent.conf .
CMD ["/fluent-bit/bin/fluent-bit", "-c", "/fb/fluent.conf"]
