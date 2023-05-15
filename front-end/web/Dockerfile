FROM node:18-alpine
RUN mkdir react-app
WORKDIR  /react-app
COPY . /react-app

RUN npm ci
RUN npm run build

EXPOSE 3000

CMD ["npm", "run", "dev"]
