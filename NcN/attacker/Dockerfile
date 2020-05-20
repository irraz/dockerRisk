FROM ubuntu:16.04
# Ejecutar con: docker run -it -p 8080:8080 attacker
RUN apt update && apt install -y netcat
CMD ["nc", "-lvp", "8080"]
