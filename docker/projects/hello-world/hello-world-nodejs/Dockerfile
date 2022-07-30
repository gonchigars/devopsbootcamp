FROM node:8.16.1-alpine
WORKDIR /app
#COPY package.json /app
#RUN npm install
EXPOSE 6000
COPY . /app
RUN npm install
#EXPOSE 6000
CMD node index.js

#ENTRYPOINT ["node", "index.js"]
#COPY package.json /app
