FROM ubuntu:20.04

RUN apt-get update
RUN apt-get install -y curl 

COPY script.sh .

RUN chmod +x script.sh

ENTRYPOINT [ "./script.sh" ]