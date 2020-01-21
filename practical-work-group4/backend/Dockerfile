FROM node:alpine

COPY ./ /opt/app

# Add next line so that Docker will install packages automatically
RUN cd /opt/app && npm install 

WORKDIR /opt/app

CMD ["npm", "run", "dev"]