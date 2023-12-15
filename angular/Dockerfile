FROM node:14-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 4200
ENV NODE_ENV=production
CMD ["npm", "start"]

