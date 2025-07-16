ARG version
FROM almalinux:${version:-9}
ENV COURSE="DevOps" \
    DURATION="120HRS"
ARG TRAINER="SIVA"
ENV TRAINER=$TRAINER
RUN echo "HI, course is: ${COURSE}, duration is:${DURATION}, trainer is: ${TRAINER}, version: ${version}"
CMD ["sleep","1000"]