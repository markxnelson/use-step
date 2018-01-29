

When you want to run this, set these two env vars to access docker store:

```
export X_DOCKER_USERNAME="whatever"
export X_DOCKER_PASSWORD="whatever"
```

Then use the command: 

```
wercker dev --docker-local --enable-dev-steps
```
