FROM node:carbon

COPY ./ /

RUN npm install -g http-server

EXPOSE 8081
CMD ["http-server", "-p", "8081"]
