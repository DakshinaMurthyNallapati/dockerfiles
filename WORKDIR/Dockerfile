FROM almalinux:9
RUN mkdir /tmp/work-dir-demo
# RUN cd /tmp/work-dir-demo  ----> In docker cd will not work to change directory in RUN command
WORKDIR /tmp/work-dir-demo
RUN pwd
RUN echo "Hello from WORK DIR" > hello.txt
CMD ["sleep", "100"]
