
FROM node:14


WORKDIR /usr/src/app


COPY package*.json ./


RUN npm install


COPY . .


EXPOSE 5000

# Command to run the application
CMD [ "npm", "start" ]
