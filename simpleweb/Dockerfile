# Specify a base image
FROM node:14-alpine

# Install some depenendencies
COPY ./package.json ./ 

RUN npm install

COPY ./ ./
# Default command
CMD ["npm", "start"]
