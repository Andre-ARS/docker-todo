FROM node:14-alpine 
WORKDIR /back_end
ADD ./node_modules.tar.gz .
COPY . .
EXPOSE 3001
ENTRYPOINT [ "npm", "start" ]