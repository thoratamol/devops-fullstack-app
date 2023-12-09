# Use a base image with Go
FROM golang:1.16

# Set the working directory
WORKDIR /app

# Copy the backend code
COPY . .

# Build the backend application
RUN go build -o main .

# Expose port 8080
EXPOSE 8080

# Start the backend server
CMD ["./main"]

