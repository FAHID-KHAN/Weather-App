FROM node:alpine

COPY ./ /opt/app

RUN cd /opt/app && npm install && npm run build

WORKDIR /opt/app

CMD ["npm", "run", "dev"]