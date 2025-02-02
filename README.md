

## Dockerized Kannel SMS Gateway with GoIP SMPP Configuration
This project provides a Dockerized solution for deploying Kannel, an open-source SMS gateway, configured to connect to a GoIP device via the SMPP (Short Message Peer-to-Peer) protocol. Kannel is a powerful tool for sending and receiving SMS, while GoIP is a popular hardware device for managing SMS and VoIP communications. This setup ensures seamless integration between the two systems, ideal for large-scale SMS messaging applications.


# Quick Start

## 1. Clone the Repository
Clone the repository to your local machine:

```bash
git https://github.com/zlin143/kannel-docker-goip.git
cd kannel-docker-goip
```

## 2. Configure Kannel
E
dit the kannel.conf file to match your GoIP device settings:

Update the host, port, smsc-username, and smsc-password fields under the SMSC SMPP CLIENT goip section.
Adjust other settings as needed.

## 3. Start the Docker Container
Run the following command to start the Kannel SMS gateway:


```bash
docker-compose up -d
```

