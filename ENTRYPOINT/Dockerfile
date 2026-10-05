FROM almalinux:9
LABEL maintainer="chanakya <chanakya@gmail.com>"
RUN dnf install -y iputils && dnf clean all
CMD ["ping","www.google.com"]