# T4 Optimización y Documentación

## ¿Qué se entiende por hediondez del código? Pon al menos 5 ejemplos.

Es cualquier síntoma en el código fuente de un programa que posiblemente indica un problema más profundo. Las hediondeces del código usualmente no son bug de programación ni errores, ni son técnicamente incorrectos y en realidad no impiden que el programa funcione correctamente. 

En cambio, indican deficiencias en el diseño de software que puede ralentizar el desarrollo o aumentan el riesgo de errores o fallos en el futuro.

1. Código duplicado
2. Nombres de variables y métodos confusos o poco descriptivos
3. Funciones o métodos muy largos o complejos
4. Acoplamiento excesivo entre clases o módulos
5. Uso abusivo de patrones de diseño o estructuras de control anidadas.

## ¿Qué tipo de herramienta utilizamos para hacer análisis estático del código?

Mediante analizadores como los linters, aunque tambien existen otros como SonarQube, ESLint, PMD, JSHint o FindBugs, aunque tambien usamos mucho SpotBUgs en Java con el entorno de iDEA. 

## ¿Qué sitios web nos permiten hacer análisis estático del código o Continuous Inspection?

Aquí van algunas de las más usadas:

```
SonarQube
CodeClimate
Codacy
GitLab Code Quality
CircleCI Orbs
Travis CI
Jenkins
Bitbucket Pipelines
AWS CodeBuild
Azure DevOps Pipelines
```

## Instala en Intellij iDEA el plugin SpotBugs, si no lo tienes aún instalado. Realiza análisis estático de código para las clases del proyecto con bucle infinito.

Habiendo instalado el SpotBugs en **iDea IntelliJ**, hemos generado un bucle infinito para que lo detecte, pero el plug-in no funciona como debería. Intentaré actualizar esta página si consigo dar con la clave.

## ¿Qué es la refactorización?

La refactorización es el proceso de mejorar el diseño interno de un código fuente sin cambiar su comportamiento externo. El objetivo principal de la refactorización es mejorar **la legibilidad, la mantenibilidad y la escalabilidad del código**. Al refactorizar, se modifican los detalles del diseño del código, como la estructura, el estilo, la organización y el formato del código.

## ¿Qué técnicas se utilizan a menudo a la hora de refactorizar?

Algunas técnicas comunes que se utilizan al refactorizar incluyen:

- **Extracción de métodos**: Esta técnica implica la separación de un bloque de código en un método separado, lo que puede mejorar la legibilidad y la reutilización del código.

- **Consolidación de métodos**: Esta técnica implica la combinación de varios métodos en uno solo para simplificar la lógica del programa y reducir la complejidad.

- **Eliminación de código duplicado**: Esta técnica implica la identificación y eliminación de código duplicado, lo que puede mejorar la mantenibilidad y la escalabilidad del código.

- **Renombrado de variables y métodos**: Esta técnica implica cambiar el nombre de las variables y los métodos para mejorar la legibilidad del código.

- **Extracción de clases**: Esta técnica implica la creación de una nueva clase para manejar una funcionalidad específica del código, lo que puede mejorar la organización y la escalabilidad del código.

- **Cambios de diseño**: Esta técnica implica la modificación de la estructura y organización del código para mejorar su diseño general y reducir su complejidad.

