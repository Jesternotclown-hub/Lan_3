FROM nginx:latest
WORKDIR /app
COPY . .
COPY index.html /usr/share/nginx/html/
EXPOSE 8080
RUN echo "Goodbye my honey world"