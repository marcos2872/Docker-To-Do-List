FROM node:14-alpine
WORKDIR /todo-app/front-end/
COPY . .
RUN npm install
EXPOSE 3000
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]