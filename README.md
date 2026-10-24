# Calculadora de notas para aprobar — Versión 4

Diseño académico elegante vino tinto, blanco y dorado. Funciona sin instalaciones ni servidor.

## Uso
- En **nota definitiva**, escribe 40 para 4,0 y 35 para 3,5. La materia vale 80 % y el campo 20 %. Resultado: 3,90.
- En **promediar notas**, selecciona de 2 a 10 notas y escribe valores enteros de 0 a 50. Se muestra el promedio en escala 0 a 5.
- En **promedio por periodo**, introduce las notas en puntos enteros de 0 a 50.
- En **registro anual**, registra los 4 periodos; cada área promedia sus materias por periodo y suma los cuatro resultados. La meta es 120 puntos.
- En **¿cuánto necesito para aprobar?**, consulta los puntos que faltan.
- El registro anual se guarda localmente y permite exportar/importar un JSON.

## Publicación
Sube `index.html` y `README.md` a GitHub. Conecta el repositorio a Vercel y publícalo como web estática.

## Privacidad y precisión
Los datos se guardan únicamente en el navegador (localStorage), no se envían a un servidor. Las herramientas rápidas son independientes del registro anual. La aprobación definitiva depende del reglamento académico de la institución.
