FROM node:22-alpine@sha256:ab07539e0988b63558ff621f5fbe1077054c39d9809112974fb79993949d41cd

LABEL org.opencontainers.image.source="https://github.com/earlvanze/ollama-umbrel-dashboard"

WORKDIR /app

COPY --chown=node:node . /app

USER node

EXPOSE 11434

CMD ["node", "/app/server.js"]
