
# Evaluación final del módulo 1.
Este es el repositorio para el ejercicio de evaluación final del módulo 1 de [Adalab](https://adalab.es) de Soraya Valle.

La evaluación consiste en replicar el diseño de web propuesto en Zeplin acorde a las normas y los criterios exigidos por el profesorado. Dicho diseño debe ser responsive y realizado con SASS.

### Estructura de carpetas.

|Index|Partials| 
|--|--|
||Header|
||Main|
||Footer|

#### Estilos:
|SCSS|Contenido
|--|--|
|Base| Reset
|Core| Mixins / Variables
|Layouts| Structure / Header / Main / Footer
|Main| Enlaza los partials para crear el index

> Vista simplificada de la estructura.
```
/
- _src
   |- assets
   |  |- icons
   |  |- images
   |  |- js
   |  - scss
   |     - base
   |       - _reset
   |     - core
   |       - _mixins
   |       - _variables
   |     - layouts
   |       - _structure
   |       - _header
   |       - _main
   |       - _footer
   |
   - templates
   |- index
   |  |- partials
   |     - header
   |     - main
   |     - footer
```
> Vista completa de la estructura.