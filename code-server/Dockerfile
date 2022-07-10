
FROM node:16-bullseye

EXPOSE 8080

RUN apt update -y && apt install -y build-essential pkg-config python3

RUN npm config set python python3

RUN yarn global add code-server

CMD ["code-server"]
