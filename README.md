# Ejercicio Guiado: Testing Ágil y TDD en una API de Reservas de Salas


## Grupo 6


### ¿En qué se diferencia Agile Testing del enfoque tradicional?
Agile Testing se implementa desde el primer día y las pruebas se realizan de manera constante a lo largo de todo el proyecto, promoviendo la colaboración entre testers y desarrolladores. En cambio, el enfoque tradicional concentra las pruebas al final del proyecto, con una planificación rigurosa desde el inicio y equipos que trabajan por separado sin colaboración directa.

### ¿Qué ventajas viste al usar TDD? ¿Qué te costó más?

La ventaja que vimos al usar TDD es que el desarrollo esta enfocado directamente a pruebas, teniendo ya en mente lo que podria fallar y se evitan fallos comunes que podrian haber ocurrido desarrollando de la forma tradicional, ademas de apuntar a un objetivo en concreto durante la escritura de codigo, lo que más nos costo fue invertir el proceso tradicional de desarrollo/pruebas, realizando primero los pruebas antes de escribir siquiera alguna función

### ¿Qué tipo de prueba crees que más valor aportó hoy?

Las pruebas de integración, ya que con ellas se logro probar el funcionamiento real que tendria la API del ejercicio, pudiendo ver de forma clara como interactuan distintos componentes del codigo entre si

### ¿Cómo mantendrías esta suite de pruebas con el tiempo?

Mediante la automatización de pruebas, usando runners de CI/CD para que las pruebas se lleven a cabo al realizar commit de forma automatica, tambien separando las pruebas para que se ejecuten al realizar merge o pull request según sea necesario