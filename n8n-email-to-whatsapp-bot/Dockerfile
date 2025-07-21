# Step 1: Use official Node image
FROM node:18-alpine

# Step 2: Create app dir
WORKDIR /app

# Step 3: Install necessary tools
RUN apk add --no-cache bash curl python3 make g++ \
  && npm install -g n8n

# Step 4: Expose port
EXPOSE 5678

# Step 5: Default command
CMD ["n8n"]
