# kong-api-gateway-example
Example Project to run a kong api gateway with konga GUI using docker.


## Running
```
docker compose \
    --env-file ./config/.env.example \
    --profile database \
    up
```

* `--env-file` define where is the env file with environments configs.

* `--profile database` define profile to up db migrations