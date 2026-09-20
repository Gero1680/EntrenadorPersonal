# Mi Entrenador v3 — GitHub Pages

Cambios:
- Botones de semana: `sem.1`, `sem.2`, `sem.3`, `sem.4`.
- Entrenamientos: `Fuerza A`, `HIIT marcial`, `Fuerza B`, `Tábata`.
- Semana tipo visible: lunes Fuerza A, martes HIIT marcial, miércoles pádel, jueves Fuerza B, viernes Tábata, sábado descanso, domingo fútbol sala.
- Cada ejercicio muestra una imagen/esquema encontrado en la web y debajo mantiene el botón de YouTube.
- Temporizador específico por ejercicio:
  - Fuerza: contador de repeticiones + series y descanso automático de 60 s.
  - Paseos/carries: cuenta atrás por tiempo.
  - HIIT marcial: 30 s trabajo / 30 s descanso y número de intervalos según semana.
  - Tábata: 20 s trabajo / 10 s descanso × 8.
- Todos los temporizadores pueden pausarse y reiniciarse.
- Historial persistente mediante localStorage.

Las imágenes proceden de fuentes web. Para las imágenes del conjunto Free Exercise DB se usa su alojamiento público; el repositorio declara el dataset como público. El proyecto conserva los enlaces de YouTube como en v2.

Publicación: sube el contenido a la raíz del repositorio y activa Settings → Pages → Deploy from a branch → main → /(root).
