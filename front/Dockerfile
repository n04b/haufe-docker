FROM node:14

RUN mkdir -p /app
WORKDIR /app

RUN git clone https://github.com/n04b/haufe-front.git

WORKDIR /app/haufe-front
RUN npm install

EXPOSE 3000
CMD ["npm", "start"]