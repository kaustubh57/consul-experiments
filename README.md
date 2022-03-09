## consul commands
- consul agent
- consul agent -dev
- consul --version
- consul members
- consule leave
- consul agent -dev -enable-script-checks -config-dir=[CONFIG_DIR_PATH]
- dig @127.0.0.1 -p 8600 [SERVICE_NAME].service.consul
- dig @127.0.0.1 -p 8600 [SERVICE_NAME].service.consul SRV
- consul catalog nodes
- consul catalog services


## consul APIs
- /v1/catalog/nodes
- /v1/catalog/services
