ARG version
FROM almalinux:${version:-9}
ENV course="devops with AWS" \
    trainer="sivakumar" \
    duration="120hs"
ARG user=Dhanunjayareddy
RUN echo "hello :: ${user} ,image vesrion: ${version}" > /tmp/devops.txt
CMD ["sleep","100"]