markdown
# My Custom Nginx Docker Project

This repository contains the source code for a custom Nginx Docker image.

## Functionality

The `Dockerfile` builds a new image based on `nginx:alpine` and replaces the default welcome page with a custom `index.html`.

## How to Use

1.  **Build the image:**
    `docker build -t your-docker-id/my-custom-nginx .`

2.  **Run the container:**
    `docker run --name my-nginx -p 8888:80 -d your-docker-id/my-custom-nginx`

3.  Open your browser and navigate to `http://localhost:8888` to see the custom page.
