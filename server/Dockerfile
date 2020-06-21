FROM node:alpine

WORKDIR "/app"

COPY ./package.json ./
RUN npm install

COPY . .
RUN ls -al
CMD ["npm" , "run" ,"start"]