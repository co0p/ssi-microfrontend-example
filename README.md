ssi-sveltekit-example
=====================

_Experiments on building a microfrontend using ssi and sveltekit_

ssi & nginx
-----------

checkout tag XXX, build docker container and run it. Point your browser to http://localhost:8080 and you will see the two pages rendered in the container index.html 
```shell 
docker build -t ssi-sveltekit-example .
docker run -p8080:80 ssi-sveltekit-xample
```
