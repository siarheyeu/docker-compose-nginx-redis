This project demonstrates a simple Docker Compose setup with three services:

Nginx — reverse proxy

Redis — in‑memory key‑value store

Flask app — demo backend that counts visits

The goal is to show how multiple containers interact inside a single Docker Compose network.


How to Run

docker compose up -d --build


Check the app:

curl http://localhost


Expected output:

Visits: 1




