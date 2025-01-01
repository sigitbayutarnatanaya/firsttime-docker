FROM node:14

WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Set environment variables
ENV CI=true
ENV WDS_SOCKET_PORT=0

EXPOSE 3000
CMD ["npm", "start"]