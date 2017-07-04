From node:boron

#Create app directory
Run mkdir -p /usr/src/app
WORKDIR /usr/src/app

#Install app dependencies
COPY package.json /usr/src/app
RUN npm install
RUN npm link mongodb
RUN npm link monk

#Bundle app source
COPY . /usr/src/app

EXPOSE 8080
CMD [ "npm", "start" ]
