FROM node:12.18.3

RUN mkdir /app
COPY ../react-frontend/* /app/

RUN echo $PWD
RUN ls -al /app

WORKDIR /app
RUN npm install

CMD ["npm", "start"]
