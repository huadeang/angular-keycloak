
## Register Plugin
```sh
curl -s -X POST http://localhost:8001/plugins \
  -d name=oidc \
  -d config.client_id=kong \
  -d config.client_secret=ocTrWxk3eF3KkYT9LFuAcS5IVe8glilU \
  -d config.bearer_only=yes \
  -d config.realm=angular \
  -d config.introspection_endpoint=http://keycloak:8080/realms/angular/protocol/openid-connect/token/introspect \
  -d config.discovery=http://localhost:8080/realms/angular/.well-known/openid-configuration
```

http://localhost:8080/realms/angular/protocol/openid-connect/token/introspect