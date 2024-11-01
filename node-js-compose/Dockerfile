# Base image - Here we specify the base image for our container
FROM node:slim 
# Working directory - Here we specify the working directory for our container
WORKDIR /app
#COPY - Here we copy the application files to the working directory
COPY . /app
# Install dependencies - Here we install the dependencies for our application on the container
RUN npm install
# Expose port - Here we expose the port on which our application will run
EXPOSE 3000
# Start the application - Here we start the application
CMD node index.js