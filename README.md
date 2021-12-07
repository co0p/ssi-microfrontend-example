ssi-sveltekit-example
=====================

_Experiments on building a microfrontend using ssi and sveltekit_

```shell 
docker build -t ssi-sveltekit-example .
docker run -p8080:80 ssi-sveltekit-xample
```


ssi & nginx
-----------

checkout tag [v1-flat](https://github.com/co0p/ssi-sveltekit-example/releases/tag/v1-flat), build the docker container and run it. Point your browser to http://localhost:8080 and you will see the two pages rendered in the container index.html 

spa style
---------
checkout tag [v2-spa](https://github.com/co0p/ssi-sveltekit-example/releases/tag/v2-spa), build the docker container and run it. Point your browser to http://localhost:8080 and you will see the two pages rendered in the container index.html. When
you click a link, you will have a spa experience. SSI replaces the placeholder with the content of the respective html page.
