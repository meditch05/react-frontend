FROM node:12.18.3

RUN mkdir /app
COPY * /app/
WORKDIR /app

RUN echo $PWD
RUN ls -al /app

RUN npm install react-scripts@3.4.3 -g

CMD ["npm", "start"]
