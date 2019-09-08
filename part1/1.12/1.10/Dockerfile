FROM node:11

WORKDIR /app
COPY frontend-example-docker /app
RUN npm install
CMD API_URL=http://localhost:8888 npm start

