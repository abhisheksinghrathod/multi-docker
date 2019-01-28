FROM node:alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm imstall
COPY . . 
CMD ["npm", "run", "start"]