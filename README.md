# Flexbox Chat — Ejercicio de CSS Avanzado

Interfaz de chat desarrollada como ejercicio del **Módulo de CSS Avanzado
(Flexbox)** de mi formación en Desarrollo Web Front-End con Desafío Latam.

Este proyecto es la **quinta pieza de mi portafolio**, después de
`01-curriculum-futbolista` (HTML básico), `02-curriculum-vitae-jferro`
(Bootstrap 5), `03-pizzeria-ramos` (CSS) y `04-flexbox-iguana` (Flexbox).
Aquí profundicé en Flexbox aplicándolo a una interfaz real tipo chat.

---

## 🎯 Objetivo

Practicar Flexbox en un layout de aplicación real:

- **Layout de dos columnas:** sidebar + área principal
- **Lista vertical de contactos** con Flexbox
- **Alineación horizontal** de foto + texto + iconos
- **Distribución con `justify-content`** (space-between, center)
- **Alineación vertical con `align-items`**
- **Botones y estilos** con transiciones suaves
- **Responsive design** con media queries

---

## 🛠️ Tecnologías usadas

- **HTML5** — estructura semántica
- **CSS3** — estilos, Flexbox, responsive
- **Google Fonts (Roboto)** — tipografía
- **Font Awesome** — iconografía

---

## 📁 Estructura del proyecto

```
flexbox-chat/
├── index.html
├── README.md
├── .gitignore
├── .nojekyll
└── assets/
    ├── css/
    │   └── style.css       ← estilos propios
    └── image/
        ├── maria.jpg
        ├── juanita.jpg
        ├── alberto.jpg
        ├── ignacio.jpg
        ├── cristian.jpg
        ├── maria-jose.jpg
        ├── gonzalo.jpg
        ├── juan-pablo.jpg
        ├── magdalena.jpg
        └── hand.png
```

---

## 🎨 Secciones del sitio

1. **Sidebar (izquierda)**
   - Contacto destacado: María
   - Botón "Nuevo Chat"
   - Lista de contactos con foto, nombre y mensaje
2. **Sección principal (derecha)**
   - Imagen ilustrativa (manos chocando)
   - Título "Comienza el Networking"
   - Texto descriptivo

---

## 🧠 Aprendizajes

- **Flexbox en profundidad:**
  - `display: flex` en layouts de dos columnas
  - `justify-content: space-between` para distribuir
  - `align-items: center` para alinear verticalmente
  - `flex-direction: column` para listas verticales
  - `flex-shrink: 0` para evitar que un elemento se encoja
  - `gap` para separar elementos

- **Reset CSS** con `*`:
  - `margin: 0; padding: 0; box-sizing: border-box;`

- **Estilos coherentes:**
  - Paleta de colores (morado `#a491d2`, grises)
  - Tipografía Roboto con peso 300
  - Transiciones suaves (`transition: 0.5s`)

- **Responsive design:**
  - `@media (max-width: 768px)` para adaptar el layout a móvil
  - `max-width: 100%` en imágenes

- **Buenas prácticas:**
  - `alt` descriptivo en todas las imágenes
  - Nombres de imágenes sin espacios ni mayúsculas
  - Estructura semántica (`main`, `aside`, `section`)
  - Código comentado por secciones

---

## 📅 Línea de tiempo

- **Septiembre 2024** — Ejercicio original del Módulo de CSS Avanzado (Flexbox) en Desafío Latam
- **Octubre 2026** — Revisión, corrección de errores y limpieza del código
- **Octubre 2026** — Publicado en GitHub como pieza de portafolio

---

## 👤 Autor

**Joaquín Ferro Vasco**
- 🎨 Diseñador Gráfico | Desarrollador Front-End en formación
- 📧 [joaquin.ferro@gmail.com](mailto:joaquin.ferro@gmail.com)
- 🐙 [GitHub](https://github.com/JoaquinFerro)
- 💼 [LinkedIn](https://www.linkedin.com/in/joaquin-felipe-ferro-vasco-b5a77046)
- 🌐 [Portafolio personal](https://joaquinferro.github.io/02-curriculum-vitae-jferro/)

---

*Este proyecto forma parte de mi proceso de aprendizaje en desarrollo
front-end. Agradezco cualquier comentario o sugerencia.*