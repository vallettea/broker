FROM ants/nodejs:v1
MAINTAINER Alexandre Vallette <alexandre.vallette@ants.builders>

ADD .tmp/ /broker/

RUN cd broker && npm install
EXPOSE 4000
CMD cd broker && forever server.js