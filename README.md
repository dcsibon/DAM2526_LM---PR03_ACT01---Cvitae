## Actividad 1: CVitae en XML

Crea un documento XML llamado `cv.xml` que represente el currículum vitae de una persona.

El documento debe tener como elemento raíz `<cv>` y organizar la información de forma jerárquica. Para ello, ten en cuenta las siguientes agrupaciones:

* Los datos de residencia (**ciudad** y **país**) deben ir dentro de un elemento `<residencia>`.
* Los datos de contacto (**teléfono**, **email** y **LinkedIn**) deben agruparse dentro de `<contacto>`.
* Las competencias deben agruparse dentro de `<competencias>`, utilizando elementos `<competencia>` con atributos para el nombre y el nivel.
* La formación debe agruparse dentro de `<formacion>`.
* La experiencia profesional debe agruparse dentro de `<experiencia-profesional>`, incluyendo al menos una experiencia con sus datos.

Utiliza los siguientes datos para construir el XML:

| Dato              | Valor                                                                |
| ----------------- | -------------------------------------------------------------------- |
| Nombre            | Shigeru Miyamoto                                                     |
| Año de nacimiento | 1987                                                                 |
| Ciudad            | Kioto                                                                |
| País              | Japón                                                                |
| Teléfono          | +81-555-11-33-66                                                     |
| Email             | [shigeru@servidordecorreo.jp](mailto:shigeru@servidordecorreo.jp)    |
| LinkedIn          | [http://www.linkedin.com/miyamoto](http://www.linkedin.com/miyamoto) |
| Descripción       | Gran capacidad creativa. Interesado en el diseño de videojuegos.     |

### Competencias

| Nombre            | Nivel |
| ----------------- | ----- |
| Diseño            | Alto  |
| Trabajo en equipo | Medio |
| Música            | Alto  |

### Formación

| Titulación        | Centro                                              | Año  |
| ----------------- | --------------------------------------------------- | ---- |
| Diseño industrial | Colegio Municipal de Artes Industriales de Kanazawa | 2009 |

### Experiencia profesional

| Puesto              | Empresa | Inicio | Fin             |
| ------------------- | ------- | ------ | --------------- |
| Diseñador de juegos | Nitendo | 2012   | (sin finalizar) |

El documento debe estar bien formado y estructurado correctamente.
