# Use the official Node.js 14.x image with Alpine Linux as the base image
FROM node:14-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy your application files into the container
COPY . .

# Install project dependencies
RUN dotnet add package Microsoft.EntityFrameworkCore

# Expose the port that your Node.js app will listen on (adjust this as needed)
EXPOSE 4000

# Specify the command to start your Node.js application
CMD ["dotnet", "PoojaStores.sln"]
