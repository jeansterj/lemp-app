FROM node:18-alpine3.14
    
RUN npm install -g @vue/cli

RUN mkdir -p /app

WORKDIR /app

COPY . /app

RUN npm install
RUN npm add serve

CMD [ "npm", "run", "serve" ]
