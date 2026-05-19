# DAW Quiz 🎓

Juego de preguntas tipo test para repasar las asignaturas de **1º de DAW**.

---

## Archivos

```
DAW-Quiz/
├── quiz-daw.html     # El juego (abre esto en el navegador)
└── preguntas.js      # Banco de preguntas (edita aquí para añadir más)
```

---

## Cómo ejecutar

Doble clic en `quiz-daw.html`. Se abre directamente en el navegador, sin instalaciones ni conexión a internet.

> Con VS Code: instala la extensión **Live Server**, haz clic derecho sobre `quiz-daw.html` → *Open with Live Server*.

---

## Modos de juego

| Modo | Descripción |
|------|-------------|
| 📖 **Modo asignatura** | 30 preguntas de una sola materia |
| 🎓 **Modo examen** | Todas las asignaturas. Una ruleta elige la materia en cada turno |
| ⚔️ **Modo desafío** | 2 a 4 jugadores por turnos en el mismo dispositivo |

---

## Puntuación

- ✅ Acierto → **+1 punto**
- ❌ Cada 3 fallos → **−1 punto**
- ⏭️ Pasar → sin penalización

El juego termina cuando se completan los 30 peldaños de cada asignatura.

---

## Asignaturas incluidas

- 🔵 Lenguaje de Marcas
- ⭐ Módulo Profesional Optativo
- 🟢 Programación
- 🗄️ Bases de Datos
- 🟠 Entornos de Desarrollo
- 💼 Empleabilidad
- 🔴 Sistemas Informáticos

---

## Añadir preguntas

Abre `preguntas.js` y añade objetos al array de la asignatura correspondiente:

```js
{
  q: "¿Texto de la pregunta?",
  a: 2,                              // Índice de la respuesta correcta (0-3)
  opts: ["Opción A", "Opción B", "Opción C correcta", "Opción D"]
}
```

---

*Creado con Claude · DAW 1º · 2025*
