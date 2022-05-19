FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
ADD node_modules.tar.gz /tests
COPY . .
RUN npm install
ENV FRONT_HOST=localhost FRONT_PORT=3000
ENTRYPOINT ["npm test"]
