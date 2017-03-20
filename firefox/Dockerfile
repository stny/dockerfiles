FROM ubuntu:16.04

RUN apt-get update && apt-get install -y \
  firefox \
  pulseaudio \
  fonts-ipafont-gothic fonts-ipafont-mincho \
  && rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["firefox"]
