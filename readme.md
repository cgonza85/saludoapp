# GRUPO 9 Ejercicio Guiado: Automatización del Proceso de Construcción con Jenkins y Java

## ¿Qué beneficios concretos viste al automatizar la construcción con Jenkins?

Detecta errores de forma temprana, reduce los errores humanos, mejora la calidad del software y al disponer de la automatización se pueden generar entregas más seguidas.

## ¿Qué parte del proceso crees que sería más crítica en un equipo grande?

La parte de las pruebas automaticas, ya que de esta forma se puede colaborar de forma más segura en un equipo grande.

## ¿Cómo Jenkins asegura calidad antes de hacer despliegues?

Permite tener una variedad de pasos, ya sean pruebas o validaciones de despliegue que permiten que cada vez que se ejecute pase por estos pasos automatizados, garantizando que los despliegues a producción cuenten con un estándar de calidad.


## ¿Qué cambiarías en este pipeline para prepararlo para producción?

Añadir una etapa de despliegue automatizado, hacia un contenedor docker. 
Incluir notificaciones por correo o Slack, informando sobre despliegues exitosos o fallidos.
Añadir más validaciones con pruebas unitarias.
Subir artefactos a repositorios centrales como Nexus.
Tener un versionado para un mejor registro de los cambios

Prueba de ejecución: console-output.log y ejecucioncorrecta.jpeg