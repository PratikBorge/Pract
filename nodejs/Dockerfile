FROM ubuntu:22.04
LABEL engg="prat"

USER root
RUN apt update
RUN apt install nodejs npm -y
RUN git clone https://github.com/owanhunte/nodejs-chat-app.git
WORKDIR /nodejs-chat-app
RUN npm install
EXPOSE 3000

CMD [ "npm" ,"start" ]