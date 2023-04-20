FROM node:12-alpine
WORKDIR /app
VOLUME ["/app"]
RUN npm install -g nodemon
CMD ["nodemon", "-L", "shipping-service/index.js"]