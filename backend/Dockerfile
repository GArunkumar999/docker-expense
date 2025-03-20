FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js . 
RUN npm install 
ENV DB_HOST="mysql-dev.devopslearning.fun"
EXPOSE 8080
CMD ["node", "index.js"]


# must give space for docker var