FROM alpine

ADD ./dockerfile/zeljko.repo /etc/yum.repos

# Install cool software
RUN apk add bash nmap

ENTRYPOINT ["/usr/bin/nmap"]
CMD ["-sn", "172.17.0.0/24"] 
