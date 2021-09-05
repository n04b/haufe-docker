FROM node:14

RUN mkdir -p /app
WORKDIR /app

RUN git clone https://github.com/n04b/haufe-back.git

WORKDIR /app/haufe-back
RUN npm install

EXPOSE 2000
CMD ["npm", "start"]