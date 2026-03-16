# Tarea2-cicd


Manual de Implementación CI/CD con GitHub Actions y GitHub Pages

Este manual describe el proceso de implementación de un flujo básico de Integración Continua y Despliegue Continuo (CI/CD) utilizando GitHub Actions y GitHub Pages.

El objetivo del proyecto es demostrar cómo automatizar el despliegue de un sitio web estático mediante herramientas gratuitas disponibles en GitHub, permitiendo que cada actualización del repositorio se publique automáticamente en internet sin intervención manual.

La automatización de procesos de desarrollo y despliegue es una práctica fundamental en el desarrollo moderno de software, ya que mejora la eficiencia, reduce errores humanos y garantiza que las aplicaciones se mantengan actualizadas de forma continua.


1. Creación del repositorio en GitHub

El primer paso consiste en crear un repositorio en GitHub que contenga los archivos necesarios para el sitio web y para la configuración del pipeline de CI/CD.

En este proyecto se creó el repositorio:

Tarea2-cicd

Dentro del repositorio se incluyen los siguientes archivos:

index.html

style.css

README.md

.github/workflows/deploy.yml

Estos archivos representan la estructura básica del proyecto.



2. Desarrollo del sitio web estático

Se desarrolló un sitio web sencillo utilizando HTML y CSS. El sitio contiene una página principal que describe el propósito del proyecto y las tecnologías utilizadas.

El objetivo del sitio no es su complejidad visual, sino servir como ejemplo funcional para demostrar la automatización del despliegue mediante CI/CD.

Las tecnologías utilizadas fueron:

HTML

CSS

GitHub

GitHub Actions

GitHub Pages



3. Configuración del pipeline CI/CD

Para implementar el flujo de CI/CD se creó un archivo de configuración llamado:

deploy.yml

Este archivo se encuentra dentro de la carpeta:

.github/workflows/

El archivo define un workflow de GitHub Actions que se ejecuta automáticamente cada vez que se realiza un cambio en la rama principal del repositorio (main).

El pipeline realiza las siguientes tareas:

Descargar el repositorio

Configurar el entorno de GitHub Pages

Preparar los archivos del sitio web

Publicar automáticamente el sitio en GitHub Pages



4. Ejecución automática del pipeline

Una vez configurado el workflow, cada vez que se realiza un commit o push en el repositorio, GitHub Actions ejecuta automáticamente el pipeline.

Durante esta ejecución el sistema:

descarga el proyecto

prepara los archivos del sitio

genera un artefacto del proyecto

despliega el sitio en GitHub Pages

En el panel de Actions de GitHub se puede observar la ejecución del workflow y verificar que el proceso se completó correctamente.



5. Publicación del sitio web

Después de que el pipeline se ejecuta con éxito, el sitio web se publica automáticamente utilizando GitHub Pages.

La configuración del despliegue puede verificarse en:

Settings → Pages

Donde se observa que la fuente de despliegue es GitHub Actions.



6. Acceso al sitio publicado

Una vez completado el despliegue, el sitio web queda disponible públicamente en la siguiente dirección:

https://raianneuned.github.io/Tarea2-cicd/

Esto demuestra que el flujo de CI/CD funciona correctamente y que el sitio se publica automáticamente cada vez que se realizan cambios en el repositorio.




7. Beneficios del uso de CI/CD

La implementación de CI/CD en proyectos de desarrollo ofrece múltiples ventajas:

automatización del despliegue

reducción de errores manuales

actualizaciones rápidas y seguras

mayor eficiencia en el flujo de desarrollo

facilidad para mantener aplicaciones actualizadas

Incluso en proyectos pequeños, como este sitio web estático, la automatización permite mejorar la organización del trabajo y garantizar que los cambios se publiquen de manera inmediata.



8. Conclusión

La implementación de este proyecto permitió aplicar de manera práctica los conceptos de Integración Continua (CI) y Despliegue Continuo (CD) mediante el uso de herramientas modernas como GitHub Actions y GitHub Pages.

El flujo automatizado configurado en este proyecto demuestra cómo es posible desplegar un sitio web de forma completamente automática cada vez que se realizan cambios en el repositorio.

Esta práctica evidencia la importancia de la automatización en el desarrollo de software moderno y muestra cómo herramientas accesibles y gratuitas pueden facilitar procesos que anteriormente requerían intervenciones manuales complejas.

