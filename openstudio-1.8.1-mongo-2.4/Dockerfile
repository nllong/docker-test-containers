FROM nllong/openstudio:1.8.1

RUN apt-get update -y && \
    apt-get install -y mongodb && \
    rm -rf /var/lib/apt/lists/* \
    service mongodb start

