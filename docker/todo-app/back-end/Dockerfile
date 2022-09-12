FROM node:14-alpine
WORKDIR /todo-app/back-end/
COPY . .
RUN npm install
EXPOSE 3001
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]
