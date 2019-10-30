FROM vindevoy/centos8-base:latest

RUN set -x && \ 
    dnf install --nodocs java-11-openjdk -y && \ 
    dnf autoremove -y && \ 
    dnf clean all -y && \ 
    rm -rf /var/cache/dnf

CMD ["/bin/sh"]
