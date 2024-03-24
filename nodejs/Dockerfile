FROM centos:7
LABEL engg="prat"

USER root

RUN yum update
RUN yum install git -y
RUN git clone https://github.com/owanhunte/nodejs-chat-app.git
WORKDIR /nodejs-chat-app
RUN npm install
EXPOSE 3000

CMD [ "npm" ,"start" ]