FROM node:8-alpine
MAINTAINER Hassy Veldstra <h@artillery.io>

VOLUME /artillery
WORKDIR /artillery

RUN npm install -g artillery@1.6.0-2

COPY hello.yml /artillery/hello.yml

ENTRYPOINT ["artillery"]
CMD ["--help"]