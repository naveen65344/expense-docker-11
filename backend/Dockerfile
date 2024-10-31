FROM node
RUN mkdir app
ENV DB_HOST="mysql"
WORKDIR /app
COPY *.js ./
COPY *.json ./
RUN npm install
CMD ["node", "index.js"]
