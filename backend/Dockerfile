FROM node:18

# Set working directory inside container
WORKDIR /app

# Copy package.json and package-lock.json from backend directory
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the backend code
COPY . .

# Expose the port your app listens on (example: 5000)
EXPOSE 5000

# Run the app (adjust start script if needed)
CMD ["npm", "start"]
