FROM ubuntu:20.04
RUN apt-get -y update && apt-get -y install curl nano 
COPY Files/caa/camfish/bin/ /
COPY Files/caa/camfish/.caa /root/
CMD ["/bin/bash"]
