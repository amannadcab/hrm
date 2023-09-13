FROM node:alpine
WORKDIR /app
COPY package.json ./
COPY ./ ./
RUN yarn install
EXPOSE 5000
CMD ["yarn" ,"prisma" ,"migrate" ,"dev"]