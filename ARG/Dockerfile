ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \     # passing values using ARGS during image build
    TRAINER="SINDHUJA"
ENV COURSE=${COURSE}    # calling the values using ENV inside container.
RUN echo "TRAINER: ${TRAINER}, Course: ${COURSE},VERSION: ${VERSION}"
CMD ["sleep","1000"]


