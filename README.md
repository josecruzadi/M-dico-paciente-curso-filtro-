# Médico Paciente I: estudio para el parcial

Página de estudio para el parcial de Médico Paciente I (UPAO, MEHU-837), Unidad 1: Casos Clínicos I.

## Qué incluye

- **Guía de estudio** de los 6 casos clínicos: fiebre y dengue, neumonía, síndrome coronario agudo, pancreatitis aguda, litiasis renal y ACV.
- **Práctica por tema**: 15 preguntas de opción múltiple por caso, con respuesta y explicación inmediata.
- **Simulacro**: 15, 30, 60 o 90 preguntas al azar de todos los temas, sin ver respuestas hasta el final. Al terminar muestra el puntaje por tema y un repaso de los errores.

## Cómo usarlo

Es una sola página estática (`index.html`), sin dependencias ni servidor. Ábrela en el navegador, o publícala con GitHub Pages.

### Publicar con GitHub Pages

1. Crea un repositorio público y sube `index.html` y `README.md` a la rama `main`.
2. En el repositorio, entra a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Guarda. En uno o dos minutos la página queda disponible en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Cómo editar las preguntas

Todo el contenido está en la constante `T` dentro del `<script>` de `index.html`. Cada tema tiene:

- `n`: nombre del tema.
- `g`: lista de puntos de la guía de estudio.
- `q`: lista de preguntas con este formato:

```js
["Pregunta", "Respuesta correcta", "Distractor 1", "Distractor 2", "Distractor 3", "Explicación"]
```

La respuesta correcta va siempre en la segunda posición; la página mezcla las opciones al mostrarlas.

## Referencias y aviso

Guía elaborada con Harrison, *Principios de Medicina Interna* (ed. 2023) como referencia. Es material de repaso: contrástalo con el libro y con el temario indicado por el docente. No sustituye la bibliografía del curso ni constituye guía clínica.
