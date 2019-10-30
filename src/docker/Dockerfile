FROM vindevoy/centos8-base:latest

# Install Java
RUN dnf install --nodocs java-11-openjdk -y

# Cleanup
RUN dnf autoremove -y
RUN dnf clean all -y
RUN rm -rf /var/cache/dnf

CMD ["/bin/sh"]
