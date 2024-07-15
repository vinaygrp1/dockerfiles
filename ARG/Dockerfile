ARG version
FROM almalinux:${version:-8}
ARG ${COURSE:-Docker}
ARG ${TRAINER:-Vinay}
#RUN cat /etc/*release
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}"
CMD [ "sleep","100" ]