# Enunciado didáctico reconstruido — Edición de vídeo con Media3 Transformer

Laboratorio Android para practicar una cadena sencilla de edición/exportación de vídeo con **Media3 Transformer**.

La aplicación debe:

1. seleccionar un vídeo local mediante el Storage Access Framework;
2. permitir configurar operaciones de edición sencillas: silenciar audio, rotar 90 grados y modificar la escala;
3. construir un `EditedMediaItem` con los efectos elegidos;
4. iniciar la exportación de forma asíncrona mediante `Transformer`;
5. guardar el resultado en el directorio de películas específico de la aplicación;
6. mostrar el progreso de la exportación;
7. permitir cancelar una exportación activa;
8. informar correctamente de finalización o error.

El resultado se genera como MP4; la compatibilidad real de códecs y efectos depende del dispositivo y del formato de entrada.

No existe una base de datos asociada.
