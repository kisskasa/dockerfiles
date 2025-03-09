ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG ${COURSE:-Docker}
ARG ${TRAINER:-sivakumar}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}"
CMD [ "sleep","100" ]
