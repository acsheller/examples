# Stage 1: Build stage
FROM alpine AS builder
RUN echo "Built at $(date)" > /buildinfo.txt

# Stage 2: Runtime
FROM busybox:uclibc
WORKDIR /app

# Optional: copy something from the builder
COPY --from=builder /buildinfo.txt /app/buildinfo.txt

# This will let you run the container as your user
CMD ["sh"]
