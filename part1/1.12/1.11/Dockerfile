FROM node:11

WORKDIR /app
COPY backend-example-docker /app
EXPOSE 8000
RUN npm install
CMD FRONT_URL=http://localhost:8000 npm start

