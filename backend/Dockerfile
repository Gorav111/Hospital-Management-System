# Use Node.js LTS image
FROM node:18

# Create app directory
WORKDIR /app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Copy app source
COPY . .

# App binds to port 5000 (change if needed)
EXPOSE 4000

# Command to run app
CMD ["npm", "start"]
