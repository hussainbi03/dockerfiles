FROM almalinux:9
RUN mkdir /tmp/work-dir-daemon
#workdir is like cd command
WORKDIR /tmp/work-dir-daemon  
RUN pwd
RUN echo "hello from work dir" > hello.txt
CMD ["sleep", "100"]