ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    engineer="Dakshina Murthy Nallapati" \
    duraion="120HRS"
ARG USERNAME=DakshinaMurthyNallapati
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "180"]
