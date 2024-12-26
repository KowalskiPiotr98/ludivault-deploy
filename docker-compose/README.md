This deployment provides ready docker-compose.yml file for Compose deployment.

Important things to note:
1. You **MUST** change the Postgres password before production deployment.
2. You should consider either adding a TLS certificate to the existing `nginx.conf` file, or putting this entire thing behind another reverse proxy handling the certificate. As is, the app will be available on port 8080 with no encryption.
