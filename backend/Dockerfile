FROM node
RUN mkdir app
WORKDIR app
COPY *.js .
COPY *.json .
RUN npm install
CMD ["node","index.js"]