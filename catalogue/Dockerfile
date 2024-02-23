FROM node:18.19.1-alpine3.18
EXPOSE 8080
WORKDIR /opt/server
ENV MONGO=true
COPY package.json /opt/server/ 
COPY server.js /opt/server/
RUN npm install
CMD ["node", "server.js"]

# COPY = copying pakage.json & server.js to opt/server/
# we don't write any .js, or .json files, only developers write them.
# we don't even write dockerfiles, only guide developers to write them.
# we write in K8s
