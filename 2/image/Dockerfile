FROM node

ADD package.json ./app/
ADD /src/ ./app/src/

WORKDIR /app

RUN npm install
CMD ["npm", "start"]
