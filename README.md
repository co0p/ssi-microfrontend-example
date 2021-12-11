ssi-microfrontend-example
=====================

_Experiments on building a microfrontend using ssi and sveltekit_

```shell 
docker build -t ssi-microfrontend-example .
docker run -p8080:80 ssi-microfrontend-xample
```


ssi & nginx
-----------

checkout tag [v1-flat](https://github.com/co0p/ssi-microfrontend-example/releases/tag/v1-flat), build the docker container and run it. 
Point your browser to http://localhost:8080 and you will see the two pages rendered in the container index.html 

spa style
---------
checkout tag [v2-spa](https://github.com/co0p/ssi-microfrontend-example/releases/tag/v2-spa), build the docker container and run it. 
Point your browser to http://localhost:8080 and you will see the two pages rendered in the container index.html. When
you click a link, you will have a spa experience. SSI replaces the placeholder with the content of the respective html page.

html microfrontends
--------------------
checkout tag [v3-html](https://github.com/co0p/ssi-microfrontend-example/releases/tag/v3-html), run `docker-compose build` 
to build the docker containers and run `docker-compose up` to start them. 
Point your browser to http://localhost:8000 and you will see the container index.html. When
you click a link, you will have a spa experience but this time html is served from other services. 
SSI replaces the placeholder with the content of the respective html page with a proxy request under the hood.

