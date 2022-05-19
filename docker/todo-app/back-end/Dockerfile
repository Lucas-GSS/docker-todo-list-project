FROM node:14-alpine AS todobackend
WORKDIR /backend
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
CMD ["npm", "start"]