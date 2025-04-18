FROM node:16-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ENV PORT=3005
ENV MONGO_URI=mongodb+srv://khadijakhalid2557:hybPGAdlVi13PeaF@customer-services.gxk3r0x.mongodb.net/
EXPOSE 3005
CMD ["node", "index.js"]