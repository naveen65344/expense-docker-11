FROM node
RUN mkdir app
RUN WORKDIR app
COPY *.js app
COPY *.json app
RUN npm install
CMD ["node","index.js"]