# Calculadora de notas para aprobar — versión 3

Sitio web estático con diseño académico en vino tinto, blanco y detalles dorados.

## Cómo usar

1. Abre `index.html` en Chrome, Edge o Safari.
2. En la portada aparece la calculadora de nota definitiva: materia 80 % + campo 20 %.
3. Selecciona uno de los cuatro módulos: registro anual, promedio por periodo, promedio de 2 a 10 notas o meta restante.
4. El registro anual admite 4 periodos por materia, en puntos de 0 a 50. Una materia puede alcanzar 120 puntos por separado; cada área promedia sus materias por periodo y suma los 4 resultados.
5. El registro anual se guarda en el navegador. Exporta un JSON para conservar una copia o importar tus notas después.

## Publicar en GitHub y Vercel

Sube `index.html` y `README.md` a un repositorio de GitHub. En Vercel selecciona el repositorio y despliega como sitio estático, sin comando de compilación.

## Notas

- No requiere dependencias, API, servidor ni base de datos.
- No envía datos personales a servidores.
- Las calculadoras de periodo y promedio rápido son independientes del registro anual.
- Se conservan, si existen, notas del almacenamiento de la versión anterior en el mismo navegador y origen web.
- La promoción académica real depende de las reglas oficiales de la institución.
