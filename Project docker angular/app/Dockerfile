FROM node:13
RUN mkdir -p //app
WORKDIR /app
copy package*.json /app/
RUN npm install
copy . /app/
EXPOSE 4200
CMD ["npm","start"]
