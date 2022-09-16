FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

ARG DEFAULT_PORT_NYA=80

ENV PORT $DEFAULT_PORT_NYA

EXPOSE $PORT

#VOLUME ["/app/feedback"]

CMD ["npm","start"]

