FROM node
RUN mkdir app
WORKDIR app
COPY *.js app
COPY *.json app
RUN npm install
CMD ["node","index.js"]