# Description
Simple out-of-the-box trashmailer that receives catch-all-style mails on the host and exposes them via web, using a mail-server and web-server bundled together by using docker-compose

# Install

- `git clone this Repository`
- `mkdir -p mails/incoming`
- `docker-compose up -d`

## Ports
- Web-Server is using port 80
- Mail-Server is using port 25