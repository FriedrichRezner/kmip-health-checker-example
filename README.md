# kmip-health-checker-demo

kmip-health-checker-demo is a fully configured example for the kmip-health-checker repository.

It uses pykmip as the KMIP server and generated cert and key files both on the server and for the client.

Both services are orchestrated using a docker-compose.yaml.

# Getting started

Execute `docker-compose up -d` and you should find your health checker here:

http://localhost:3322/health