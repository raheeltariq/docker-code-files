FROM alpine
LABEL maintainer="raheel@itechnets.com"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Raheel Tariq"
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"]
