### Traefik 2.x + Wildcard Certificates via LetEncrypt

This is a docker-compose stack that uses LetsEncrypt's dnsChallenge method to enable wildcard certificates.

The example app is a simple Nginx container pointed to a local directory to serve index.html.