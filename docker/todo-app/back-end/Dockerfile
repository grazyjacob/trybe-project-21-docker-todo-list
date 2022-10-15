FROM node:16-alpine
WORKDIR /todo-app/back-end
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
ENTRYPOINT [ "npm", "start"]

