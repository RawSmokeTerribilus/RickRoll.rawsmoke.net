# 🎵 RickRoll Web Project 🎵

Welcome to the most unexpected and hilarious project i ever did! 🎉

## What is this?

This is a RickRolling web project that we whipped up in just 5 minutes. Yes, you read that right. In just 5 minutes, we created a web page that RickRolls anyone who visits it. 

## How does it work?

1. **Docker Compose with Nginx**: We used Docker Compose to set up an Nginx server. This makes it super easy to deploy and manage.
2. **Two Simple Files**: The entire project consists of just two files:
   - `index.html`: The main web page that plays the RickRoll video.
   - `Rick Roll.ia.mp4`: The video file, https://archive.org/download/rick-roll/Rick%20Roll.mp4 (so no copyright issues here!).
3. **Port 81**: We changed the port to 81 to avoid conflicts with other HTTP services running on the server.
4. **Cloudflare Tunnel**: To serve the site over HTTPS and avoid exposing our server directly to the internet, we routed it through a Cloudflare tunnel.

## Demo

Check out the live demo at [https://owo.rawsmoke.net](https://owo.rawsmoke.net) and get RickRolled! 😆

## How to Run

1. Clone this repository.
2. Make sure you have Docker and Docker Compose installed.
3. Run the following command:
   ```sh
   docker-compose up -d
   ```
4. Route the site via your Cloudflare tunnel URL.


## Why Did We Do This?

Because why not? Everyone needs a good laugh, and what better way to do it than with a classic RickRoll? Plus, it's a fun way to demonstrate how quickly you can set up a web project with modern tools.

## Disclaimer

This project is for fun and educational purposes only. Use it responsibly and don't annoy people too much! 😉

Enjoy RickRolling!

