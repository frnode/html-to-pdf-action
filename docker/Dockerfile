FROM buildkite/puppeteer:latest

LABEL MAINTAINER="frnode"

ENTRYPOINT ["node", "/lib/main.js"]

COPY . .

RUN npm install --production
