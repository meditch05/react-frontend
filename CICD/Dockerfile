FROM node:12.18.3

RUN mkdir /app

# listen port
EXPOSE 3000

COPY ../react-frontend /app/

WORKDIR /app
RUN echo $PWD
RUN ls -al .
RUN ls -al /app

# RUN npm install


CMD ["npm", "start"]
