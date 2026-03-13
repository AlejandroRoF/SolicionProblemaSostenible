# CODIGO MAL OPTIMIZADO
En este proyecto vamos a dar solución a un problema que es más común de lo que pensamos en la sociedad moderna y no es otro que la cantidad de software que utiliza un código mal optimizado, este problema puede parecer imperceptible pero en este proyecto vamos a dar a la luz los verdaderos problemas sostenibles que se pueden provocar realizando esta mala práctica.

> ## SOLUCIÓN 1 OPTIMIZACIÓN DEL CÓDIGO

La solución que he desarrollado para dar solución este problema consiste en **optimizar** directamente las líneas de código asumiendo que gran parte de este código se basa en líneas obsoletas que ya no sirven para nada.

Esto suele ser así debido a la creación de parches sobre el código sin hacer un saneamiento sobre este.

Como ejemplo podemos estudiar el caso de **OpenVPN**, OpenVPN como su nombre indica es una VPN, el caso es que su código esta muy mal optimizado y tal es así que solo comparando con su competencia podemos observar como de mal esta ya que **wireguard** que es otra VPN de uso profesional unicamente tiene _4.000_ líneas de código frente a las _400.000_ de OpenVPN, esto hace que wireguard sea más atractiva frente a los clientes ya que es más rápida e incluso tiene menos brechas de seguridad, además que a la hora de mantener el código es mucho más fácil.

***

>## Solución 2: Monolito Modular

Un **monolito modular** es una aplicación única que internamente está organizada en modulos independientes a nivel lógico, donde cada modulo se encarga de una parte diferente del programa pero se ejecuta como un solo programa, y una vez ejecutado cada modulo actua también de forma independiente reduciendo el consumo de infraestructura y/o recursos, simplifica el mantenimiento del propio software.

A nivel de insfraestructura sin los modulos tendriamos varios microservicios desplegados en docker, kubernetes, bases de datos, etc, junto a varios despliegues, pipelines, contenedores, loggings, etc; con un monolito modular tendríamos un único servicio con varios modulos, un único despliegue, un único pipeline y un único sistema de logs (y un único contenedor si se da el caso).

Aunque los monolitos modulares no tienen impacto directamente sobre el código (aunque si en la manera de plantearlo), si que optimiza la comunicación entre servicios, simplifica el flujo de ejecución y despliegue y permite un mayor control sobre el uso de los recursos de la aplicación, haciendo que el código y dicha aplicación sean más sostenibles.
***