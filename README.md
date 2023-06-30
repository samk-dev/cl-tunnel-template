# Cloudflare docker tunnel template

I use this in my homelab to expose some of my backend services to the public internet for testing and sharing work with clients.

## Usage

1. Clone the repository
2. Replace the token variable in .env with your cloudflare tunnel
3. Make sure the services you want to expose are running on the same network
4. run `docker compose up -d`

⚠️ PRIVACY NOTICE ⚠️

Make sure the services that you expose to the public does not have sensitive data, and complie with GDPR because CLOURDFLARE can read all the traffic. If privacy is a concern please checkout services like ngrok or expose.dev.
