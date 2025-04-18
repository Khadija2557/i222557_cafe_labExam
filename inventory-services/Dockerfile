FROM node:16-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ENV PORT=3004
ENV MONGO_URI=mongodb+srv://khadijakhalid2557:atLqlrIWXjLCloyO@inventory-services.hn9btiu.mongodb.net/
EXPOSE 3004
CMD ["node", "index.js"]