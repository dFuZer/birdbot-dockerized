FROM node:23.7-alpine
WORKDIR /app
COPY package.json package-lock.json ./ 
RUN npm install
COPY . .
ENV NODE_ENV=production
EXPOSE 3000
RUN npm run build
CMD ["npm", "run", "start"]
