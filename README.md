## consul commands
- consul agent
- consul agent -dev
- consul agent -server
- consul agent -config-dir=[CONFIG_DIR_PATH]
- consul --version
- consul members
- consule leave
- consul agent -dev -enable-script-checks -config-dir=[CONFIG_DIR_PATH]
- dig @127.0.0.1 -p 8600 [SERVICE_NAME].service.consul
- dig @127.0.0.1 -p 8600 [SERVICE_NAME].service.consul SRV
- consul catalog nodes
- consul catalog services
- consul kv put [STORE_PATH] [STORE_VALUE]
- consul kv put -flags=[FLAG_VALUE] [STORE_PATH] [STORE_VALUE]
- consul kv get [STORE_PATH]
- consul kv get -detailed [STORE_PATH]
- consul kv get -recurse
- consul kv delete [STORE_PATH]
- consul joiin [SERVER_IP]
- consul acl bootstrap
- export CONSUL_HTTP_TOKEN=[TOKEN]
- consul acl policy create -name [POLICY_NAME] -rules [RULES_CONFIG_FILE]
- consul acl policy list
- consul acl token create -description "[DESCRIPTION]" -policy-name [POLICY_NAME]

<hr>

## consul APIs
- /v1/catalog/nodes
- /v1/catalog/services

<hr>

## Terminology
- hcl - HashiCorp Configuration Languages
- kv - Key/Value
- 

<hr>

## Video tutorial
- YouTube playlist -> https://www.youtube.com/watch?v=PflcPmyxoUo&list=PLj8MfUHg1-deRx8GyZWh68FdOjypJfB1O&index=1
- 
