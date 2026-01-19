# Gunakan Node.js LTS
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy package.json
COPY package.json ./

# Install dependencies
RUN npm install

# Copy source code
COPY . .

# Expose port backend
EXPOSE 3000

# Jalankan aplikasi
CMD ["npm", "start"]
