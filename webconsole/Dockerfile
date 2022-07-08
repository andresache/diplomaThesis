FROM ubuntu:20.04
WORKDIR /home/andres/free5gc/webconsole
COPY . .
RUN apt-get update && apt-get install -y net-tools iputils-ping vim
CMD ./server -webuicfg webuicfg.yaml
#CMD ["sh", "-c", "tail -f /dev/null"]
#CMD ./server
