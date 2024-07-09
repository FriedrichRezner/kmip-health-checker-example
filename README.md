# KMIP Health Checker Example

KMIP Health Checker Example provides a fully configured ready-to-run application for
the [KMIP Health Checker repository](https://github.com/FriedrichRezner/kmip-health-checker). This demo uses `pykmip`
as the KMIP server and includes generated certificate and key files for both the server and the client. Both services
are orchestrated using a `docker-compose.yaml` file.

## Getting Started

To start the services, execute the following command:

```sh
docker-compose up -d
```

Once the services are running, you can access the health check
at: [http://localhost:3322/health](http://localhost:3322/health)
