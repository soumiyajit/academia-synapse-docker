FROM node:20-slim
WORKDIR /app
COPY backend/package*.json ./
RUN npm install --only=production
COPY backend/ .
CMD ["node", "src/app.js"]