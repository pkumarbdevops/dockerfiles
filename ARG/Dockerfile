ARG version
FROM almalinux:${version:-8}
# ARG variable before FROM will not work after FROM
RUN echo "version passed by user id: ${version}"
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
RUN echo "Course is: ${COURSE}, trainer is: ${TRAINER}"