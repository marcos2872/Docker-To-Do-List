
FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests/
COPY . .
RUN npm install
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]