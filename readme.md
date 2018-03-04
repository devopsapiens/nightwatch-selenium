# Nightwatch.js Demo

## Sitios donde hay webs que sirven para ejecutar test de este tipo
http://www.techbeamers.com/websites-to-practice-selenium-webdriver-online/


### Prerequisitos

* Tener instalado Node & NPM y Docker

### Ejecutar

1) Lanzar el script 1_run_selenium_docker.sh . En localhost:4444 se arranca el selenium Hub con los nodos firefox y chrome arrancados.

2) Lanzar el script 2_install_and_test.sh que hace un npm install y un npm test. Es el que ejecuta los test 

En nightwatch.conf.js está configurado el servidor selenium, y la web que se usa para probar. Esta seria la supuesta web de proyecto

"launch_url": "http://dev.matthewroach.me/login/",


El proyecto esta preconfigurado para lanzar test sobre browserstack.
