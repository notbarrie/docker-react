# base image
FROM node

WORKDIR /usr/app
COPY ./ /usr/app
# deps
RUN npm install

# default cmd
CMD [ "npm",  "start" ]