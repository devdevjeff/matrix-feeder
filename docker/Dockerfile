FROM node:latest
LABEL maintainer="devdevjeff <matrix-announcement-bot@nonsense.xyz>"
RUN git clone https://github.com/devdevjeff/matrix-announcement-bot /matrix-announcement-bot
WORKDIR /matrix-announcement-bot
RUN npm install
CMD node announcer.js

