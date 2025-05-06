# Dockerized Products API

A simple REST API built with Node.js and Express, fully dockerized.

## How to run


1. Clone the repository:
git clone https://github.com/nastaranmotamed/dockerized-products-api.git

2. Go to the project directory:
cd dockerized-products-api

3. Build the Docker image:
docker build -t products-api .

4. Run the container:
docker run -p 4000:3000 products-api

5. Open in browser:
http://localhost:4000/api/products
