FROM node:14.4.0-alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
CMD ["npm", "run","start"]