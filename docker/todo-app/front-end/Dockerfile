FROM node:14-alpine 
WORKDIR /test
ADD ./node_modules.tar.gz .
COPY . .
EXPOSE 3000
ENTRYPOINT [ "npm", "start" ]
