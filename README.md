# SIVeL 2 para el SJR Colombia
[![Estado Construcción](https://api.travis-ci.org/pasosdeJesus/sivel2_sjrcol.svg?branch=master)](https://travis-ci.org/pasosdeJesus/sivel2_sjrcol) [![Clima del Código](https://codeclimate.com/github/pasosdeJesus/sivel2_sjrcol/badges/gpa.svg)](https://codeclimate.com/github/pasosdeJesus/sivel2_sjrcol) [![Cobertura de Pruebas](https://codeclimate.com/github/pasosdeJesus/sivel2_sjrcol/badges/coverage.svg)](https://codeclimate.com/github/pasosdeJesus/sivel2_sjrcol) [![security](https://hakiri.io/github/pasosdeJesus/sivel2_sjrcol/master.svg)](https://hakiri.io/github/pasosdeJesus/sivel2_sjrcol/master) [![Dependencias](https://gemnasium.com/pasosdeJesus/sivel2_sjrcol.svg)](https://gemnasium.com/pasosdeJesus/sivel2_sjrcol) 

SIVeL 2 para el SJR Colombia.

### Requerimientos
* Ruby version >= 2.2
* PostgreSQL >= 9.4 con extensio��n unaccent
* Recomendado sobre adJ 5.6 (que incluye todos los componentes mencionados). 
* La cuenta desde la cual se ejecute el servidor o las pruebas debe poder abrir 2048 archivos --en adJ se establece en la clase del usuario que ejecuta en /etc/login.conf con :openfiles-cur=2048:


### Uso
Aplican las mismas instrucciones de SIVeL 2
https://github.com/pasosdeJesus/sivel2

### Arquitectura
Se usa junto con sip, sivel2_gen, sivel2_sjr, cor1440_gen y sal7711_gen ver
https://github.com/pasosdeJesus/sip
https://github.com/pasosdeJesus/sivel2_gen
https://github.com/pasosdeJesus/sivel2_sjr
https://github.com/pasosdeJesus/cor1440_gen
https://github.com/pasosdeJesus/sal7711_gen

### Despliegue de prueba en Heroku

[![heroku](https://www.herokucdn.com/deploy/button.svg)](http://sivel2sjrcol.herokuapp.com) http://sivel2sjrcol.herokuapp.com

En el despliegue en Heroku se han eliminado las ciudades.


