ARG version
FROM almalinux:${version:-9}

ENV course = "devops with aws"\
    duration = "120hrs"\
    trainer = "SivaKumar Reddy"

ARG USERNAME=ParthuReddy    
ENV USERNAME=$USERNAME
RUN echo "hello from ${USERNAME}" > /tmp/hello.txt
CMD [ "sleep" ,"250" ]