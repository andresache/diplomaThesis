FROM ubuntu:20.04

COPY . . 

RUN apt-get update && apt-get install -y net-tools iputils-ping vim

CMD ./udm -udmcfg udmcfg.yaml
#CMD ["sh", "-c", "tail -f /dev/null"]

