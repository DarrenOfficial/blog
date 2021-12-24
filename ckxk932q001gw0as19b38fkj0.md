## How to keep your public lavalink safe by proxying it trough cloudflare.

# Hello! 🌮

> **Important**: Make sure your lavalink server is running on port 80, 8080, 8880, 2052, 2082, 2086, 2095. or if you use https on your lavalink use port 443, 2053, 2083, 2087, 2096, 8443.

In this guide I will be showing you how you can protect your public lavalink server from DDoS attack, and keeping it smooth sailing!



The first steps is to add a subdomain to your cloudflare account i.e. lavalink.example.com, after you've done so you need to make sure have the orange cloud / proxy enabled.


Next create a firewall rule! This is really crucial, so head over to your cloudflare dashboard then go to "Firewall" then click "Tools" Then add Cloudflare AS `AS13335` Number in there and block it. Why? Because some attacker uses a product called Cloudflare WARP to attack your server.