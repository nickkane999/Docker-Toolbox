# Use an existing docker image as a base
FROM node:alpine


# Sets default directory to save files into as "/usr/app"
WORKDIR /usr/app


# Download nad install a dependency
COPY ./package.json ./
RUN npm install
COPY ./ ./


#Tell the image what to do when it starts as a container
CMD ["npm", "start"]