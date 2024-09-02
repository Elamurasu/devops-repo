FROM ubuntu:latest
WORKDIR /var/app
RUN apt update
RUN apt upgrade -y
RUN apt install bc -y
RUN apt install htop -y
CMD ["bc", "-i"]
