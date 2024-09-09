FROM node:18-slim

# Set the working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install
# Copy the rest of the application code
COPY . .

# Set environment variables 
ENV PORT 90

# Start the app
CMD ["node", "server.js"]
