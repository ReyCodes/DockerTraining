# Base image
FROM node:alpine

#Copy all to root folder
#
#Copy to a workdirectory
WORKDIR /app

COPY ./package.json ./

#Install some dependencies
RUN npm install
COPY ./ ./
#Default command

CMD ["npm","start"]