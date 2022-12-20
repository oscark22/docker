FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ARG DEFAULT_PORT=3000

ENV PORT $DEFAULT_PORT

EXPOSE 3000

CMD ["npm", "start"]
