FROM almalinux:9
RUN mkdir /tmp/workdir-demo
#RUN cd /tmp/workdir-demo    # cd will not work here so will use WORKDIR
WORKDIR /tmp/workdir-demo
RUN pwd
RUN echo " hello , I am in root directory" >> hello.txt
CMD ["sleep", "1000"]