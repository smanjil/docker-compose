FROM node:9.5
ADD . /vue
WORKDIR /vue
RUN apt-get update
RUN apt-get install nodejs -y
RUN apt-get install npm -y
RUN npm install
CMD npm run serve 
