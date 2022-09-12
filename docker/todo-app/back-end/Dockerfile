FROM node:14-alpine
WORKDIR /back-end
EXPOSE 3001
COPY . .
RUN npm install
# ADD node_modules.tar.gz ./docker/todo-app/back-end/Dockerfile
ENTRYPOINT ["npm", "start"]
