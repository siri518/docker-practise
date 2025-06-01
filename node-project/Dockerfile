FROM node

ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=qwerty

RUN mkdir -p node-project

COPY . devops-practise/docker-practise/node-project

CMD ["node", "devops-practise/docker-practise/node-project/server.js"]

