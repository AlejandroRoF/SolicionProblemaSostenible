# CODIGO MAL OPTIMIZADO
En este proyecto vamos a dar solución a un problema que es más común de lo que pensamos en la sociedad moderna y no es otro que la cantidad de software que utiliza un código mal optimizado, este problema puede parecer imperceptible pero en este proyecto vamos a dar a la luz los verdaderos problemas sostenibles que se pueden provocar realizando esta mala práctica.

>## SOLUCIÓN FINAL: MONOLITO MODULAR

Un **monolito modular** es una aplicación única que internamente está organizada en modulos independientes a nivel lógico, donde cada modulo se encarga de una parte diferente del programa pero se ejecuta como un solo programa, y una vez ejecutado cada modulo actua también de forma independiente reduciendo el consumo de infraestructura y/o recursos, simplifica el mantenimiento del propio software.

A nivel de insfraestructura sin los modulos tendriamos varios microservicios desplegados en docker, kubernetes, bases de datos, etc, junto a varios despliegues, pipelines, contenedores, loggings, etc; con un monolito modular tendríamos un único servicio con varios modulos, un único despliegue, un único pipeline y un único sistema de logs (y un único contenedor si se da el caso).

Aunque los monolitos modulares no tienen impacto directamente sobre el código (aunque si en la manera de plantearlo), si que optimiza la comunicación entre servicios, simplifica el flujo de ejecución y despliegue y permite un mayor control sobre el uso de los recursos de la aplicación, haciendo que el código y dicha aplicación sean más sostenibles.
***
