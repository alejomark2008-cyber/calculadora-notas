# Calculadora de notas para aprobar

Aplicación web estática, sin dependencias ni servidor. Abrir `index.html` para usarla.

## Reglas configuradas
- Cuatro periodos, calificación por materia y periodo de 0 a 50 puntos (por ejemplo, 3.5 equivale a 35).
- Cada materia acumula la suma de sus cuatro periodos.
- Cada área promedia las materias que la componen **en cada periodo**, y suma los cuatro promedios.
- Meta anual: 120 puntos por área. También se muestra el cumplimiento individual de cada materia.
- Un periodo del área se considera registrado únicamente cuando todas sus materias tienen nota, para no confundir notas pendientes con ceros.
- El estado es provisional hasta completar los cuatro periodos. Alcanzar la meta se informa de inmediato.

## Áreas
Ciencias naturales y educación ambiental (Física, Química); Ciencias sociales (Ciencias Sociales, Ciencias Económicas y Políticas); Matemáticas (Matemáticas); Humanidades (Español, Inglés); Educación física (Educación Física); Tecnología e Informática (Tecnología); Convivencia (Comportamiento).

## Publicar
Subir `index.html` y `README.md` a un repositorio GitHub. Importar el repositorio en Vercel como sitio estático (sin build) o usar GitHub Pages.

## Privacidad
Datos en `localStorage` del navegador, sin conexión a servidores. Exportar/importar JSON permite respaldar y recuperar las notas. No usar en dispositivos compartidos si se desea privacidad.

## Nota
Es una herramienta orientativa. Confirmar las reglas reales de evaluación y los nombres oficiales antes de difundirla como sistema institucional.
