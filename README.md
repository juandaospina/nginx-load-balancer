# Load Balancer Nginx

## Technologies

- FastAPI for the Python backend APIs
- NGINX for the web server
- Docker Compose for develoment

## Features

- Load balancer for the backend APIs

# Getting Started

## Installation

To install and local deployment the nginx load balancer follow this steps: 

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/juandaospina/nginx-load-balancer
    ```
2. Navigate to the project directory:
    ```bash
    cd nginx-load-balancer
    ```
3. Run docker compose
    ```bash
    docker-compose up -d --build
    ```
4. Open in your browser http://localhost or simply localhost
5. Reload and reload your page and watch as the nginx server controls the loading between the configured services