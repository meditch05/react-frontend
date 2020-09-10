FROM node:12.18.3 as builder

RUN mkdir /app

# listen port
EXPOSE 3000

COPY ../react-frontend /app/

WORKDIR /app 
RUN npm install
RUN ls -al /app

RUN echo $PWD
ENV PATH /app/node_modules/.bin:$PATH
CMD ["npm", "start"]
