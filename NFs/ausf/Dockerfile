FROM ubuntu:20.04

COPY . . 

RUN apt-get update && apt-get install -y net-tools iputils-ping vim

CMD ./ausf -ausfcfg ausfcfg.yaml
#CMD ["sh", "-c", "tail -f /dev/null"]

