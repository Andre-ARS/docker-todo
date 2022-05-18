FROM mjgargani/puppeteer:trybe1.0 
WORKDIR /front_end
ADD ./node_modules.tar.gz .
COPY . .
EXPOSE 3000
ENTRYPOINT [ "npm", "test" ]