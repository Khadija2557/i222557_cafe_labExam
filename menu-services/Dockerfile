FROM node:16-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ENV PORT=3001
ENV MONGO_URI=mongodb+srv://khadijakhalid2557:Vjmp8pPI9EvemIxf@menu-services.xbvrayu.mongodb.net/
EXPOSE 3001
CMD ["node", "index.js"]