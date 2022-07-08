FROM ubuntu:20.04

COPY . . 

RUN apt-get update && apt-get install -y net-tools iputils-ping vim

CMD ./pcf -pcfcfg pcfcfg.yaml
#CMD ["sh", "-c", "tail -f /dev/null"]

