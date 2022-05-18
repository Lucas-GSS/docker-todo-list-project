FROM node:14-alpine
WORKDIR /frontend-app
ADD node_modules.tar.gz /frontend-app/
COPY . .
RUN npm install
EXPOSE 3000
ENTRYPOINT ["npm start"]
