## start keycloak dev mode
```sh
docker-compose up

```
## Keycloak
### Keycloak Login
![keycloak login](/assets/images/keycloak1.png)

### Create realm
![keycloak login](/assets/images/keycloak2.png)

### Create kong client
![](/assets/images/keycloak-client-kong.png)

### Create angular client
![](/assets/images/keycloak-client-angular.png)

### Get public key from keycloak
![](/assets/images/keycloak-publickey.png)

**create public key pem format**
```
-----BEGIN PUBLIC KEY-----
text from key cloak popup
-----END PUBLIC KEY-----
```

# Config Kong API Gateway
![](/assets/images/konga1.png)

## Create consumer with JWT credential
![](/assets/images/konga-consumer-jwt.png)

## Enable JWT Plugin
![](/assets/images/kong-plugin.png)
