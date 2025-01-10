FROM ubuntu:latest
RUN apt update
RUN apt install -y iproute2
RUN apt install -y tcpdump
RUN apt install -y iputils-ping
RUN apt install -y traceroute
RUN apt install -y iptables
CMD ["tail", "-f", "/dev/null"]