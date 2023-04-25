# Base image
FROM node:18.14.2-alpine

# Working directory
WORKDIR /app

# Copy necessary files
COPY package*.json ./
RUN npm install

# Copy the rest of the application files
COPY . .

# Start the ReactJS application
CMD ["npm", "start"]

