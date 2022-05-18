FROM node:14-alpine
WORKDIR /app
ADD node_modules.tar.gz /app/
COPY . .
RUN npm install
EXPOSE 3001
ENTRYPOINT npm start
