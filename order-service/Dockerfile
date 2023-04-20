FROM node:12-alpine
WORKDIR /app
VOLUME ["/app"]
RUN npm install -g nodemon
CMD ["nodemon", "-L", "order-service/index.js"]