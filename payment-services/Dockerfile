FROM node:16-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ENV PORT=3003
ENV MONGO_URI=mongodb+srv://khadijakhalid2557:7vzjpcTpmtLVzcxF@cluster0.cenkuc3.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
EXPOSE 3003
CMD ["node", "index.js"]