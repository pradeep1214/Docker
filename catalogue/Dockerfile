FROM node:14
EXPOSE 8080

WORKDIR /opt/pradeep

COPY package.json /opt/pradeep/

RUN npm install

COPY server.js /opt/pradeep/

CMD ["node", "server.js"]

