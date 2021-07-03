FROM node:14-alpine
WORKDIR /usr/src/app
COPY . .
RUN npm install
EXPOSE 8088
CMD ["node", "app.js"]

# docker build -t cevheri/nodejs-receiver-example .
# docker run --rm -p 8088:8088 cevheri/nodejs-receiver-example