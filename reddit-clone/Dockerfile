FROM node:19-alpine3.15

LABEL "author"="muzafferjoya"

WORKDIR /reddit-clone

COPY . /reddit-clone
RUN npm install 

EXPOSE 3000
CMD ["npm","run","dev"]
