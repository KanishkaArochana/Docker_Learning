# Base Image
FROM node:20-alpine

# Working Directory
WORKDIR /app

# Copy the Package.json file
COPY package.json .

# Install the Dependencies
RUN npm install

# Copy the Files
COPY . .

# Run the App
CMD [ "npm" , "start" ]