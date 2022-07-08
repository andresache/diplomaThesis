FROM ubuntu:20.04

COPY . . 

RUN apt-get update && apt-get install -y net-tools iputils-ping vim iproute2

#CMD ./n3iwf-ipsec.sh && ./n3iwf -n3iwfcfg n3iwfcfg.yaml
CMD ["sh", "-c", "tail -f /dev/null"]

