FROM node:14
WORKDIR /app
EXPOSE 3001
COPY node_modules.tar.gz /app
COPY . /app
ENTRYPOINT ["npm", "start"]
