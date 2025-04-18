FROM node:16-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ENV PORT=3002
ENV MONGO_URI=mongodb+srv://khadijakhalid2557:U5zElO4L8v4T7ENL@order-services.fpdnsjw.mongodb.net/
EXPOSE 3002
CMD ["node", "index.js"]