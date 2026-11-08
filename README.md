# system-guide

The first step for every rpi is to run the new host script. Follow the instructions at infra-new-host

The next step is to setup your github runner that'll allow you to have a clean deployment process.  Follow the instructions at infra-github-runner

The next step is to setup open bao.  This is the secrets management platform.  Follow the instructions at infra-openbao

The next step is to setup your database.  Follow the instructions at infra-mongo

The next step is to setup your reverse proxy.  Follow the instructions at infra-traefik

The next step is to setup the host health check.  Follow the instructions at infra-host-healthcheck

### To add a new UI
In addition to the repository you'll also need to add an entry into the dynamic folder in infra-traefik