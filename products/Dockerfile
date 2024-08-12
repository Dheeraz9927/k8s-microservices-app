# Base image with Node.js Alpine version
FROM node:14-alpine

# Set the working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the entire source code
COPY . .

# Expose the application's port
EXPOSE 3000

# Default command to run the application
CMD ["node", "./index.js"]
