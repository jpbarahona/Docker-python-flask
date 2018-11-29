Easy starter kit docker with flask framework.

After to clone, follow the next commands.

```Shell
docker build -t docker-python-flask .
```
```Shell
docker run -d -p 5000:80 docker-python-flask
```

Image docker dependency

[kennethreitz/pipenv](https://hub.docker.com/r/kennethreitz/pipenv/)