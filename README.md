# shiny-docker

This repo is a simple example of a containerized Shiny app that you can setup co continuously build and deploy on Google Cloud Run.

You can test this app in a Docker container with:

```
docker build -t shiny-docker .
docker run --rm -ti -p 8080:8080  shiny-docker
```

You can see the app on your web browser at http://localhost:8080/

Thanks Jacqueline Nolis for https://github.com/jnolis/shiny-docker.
