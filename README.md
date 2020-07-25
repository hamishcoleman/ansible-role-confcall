
# Configure system as a conference call host

- Enabled by the presense of the approprate key in the host variables

## Jitsi

- Enabled by the presense of the "jitsi" key in the host variables
- Installs a single node jitsi instance running the latest stable release

```
jitsi:
    hostname: meet.example.com
```

The hostname is the name used in the public SSL letsencrypt certificate, this
requires that your DNS is configured before deploying this role.

This role depends on the dehydrated ansible role (see ansible-role-dehydrated)
