FROM ubuntu:20.04

COPY . . 

RUN apt-get update && apt-get install -y net-tools iputils-ping vim

CMD ./udr -udrcfg udrcfg.yaml
#CMD ["sh", "-c", "tail -f /dev/null"]

