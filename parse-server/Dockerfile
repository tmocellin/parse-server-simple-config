FROM node:8
RUN npm install -g nodemon
RUN mkdir parse
ADD . /parse
WORKDIR /parse
RUN npm install
EXPOSE 1337
CMD [ "npm", "start" ]