FROM node:11

RUN apt-get update && apt-get install git

WORKDIR /app
RUN git clone https://github.com/AntonPirinen/FS2019osa5
RUN ls -al
WORKDIR /app/FS2019osa5/bloglist-frontend
RUN ls -al
RUN npm install
EXPOSE 3000

CMD npm start


