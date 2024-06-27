ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/os-release
ARG course=docker
ARG trainer=sivakumar
ARG duration=120hrs
ENV duration=${duration}
RUN echo course is ${course}, trainer is ${trainer}  and duration is ${duration}
CMD [ "sleep", "100"]

