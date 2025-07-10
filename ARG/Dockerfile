FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG CLOUD
ARG TECH
RUN echo "CLOUD: ${CLOUD},TECH: ${TECH}"
ENV CLOUD=${CLOUD}
ENV TECH=${TECH}
CMD ["sleep","100"]