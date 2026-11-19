# 🌅 Crecimiento Diario

Página web de **crecimiento personal** con artículos cortos sobre hábitos,
disciplina, constancia, perseverancia y mentalidad. Está pensada para inspirar
y motivar con lecturas breves que se pueden terminar en pocos minutos.

🌐 **Demo en vivo:** https://angelcaldasdev.github.io/CrecimientoDiario/

---

## ✨ Contenido de la página

- **Franja superior:** frase motivadora.
- **Portada:** mensaje de bienvenida.
- **Artículos:** tarjetas con **filtros por categoría**; las categorías se crean solas a partir de los artículos.
- **Ventana de lectura:** al abrir un artículo se muestra completo, sin salir de la página.
- **Pie de página:** enlaces de contacto.

---

## 🛠️ Tecnologías utilizadas

| Área | Tecnologías |
|------|-------------|
| Maquetación | HTML5 |
| Estilos | CSS3 (diseño responsive y variables CSS) |
| Interactividad | JavaScript (sin librerías) |
| Control de versiones | Git y GitHub |
| Publicación | GitHub Pages |

---

## 🏷️ Categorías actuales

Perseverancia · Hábitos · Mentalidad · Productividad · Disciplina · Constancia · Trabajo duro

---

## 🗂️ Estructura del proyecto

```
CrecimientoDiario/
├── index.html      # Estructura de la página
├── style.css       # Estilos
├── funciones.js    # Lógica: tarjetas, filtros y ventana de lectura
├── articulos.js    # Lista de artículos (aquí se publica contenido nuevo)
├── favicon.svg     # Ícono de la pestaña
└── README.md
```

---

## ▶️ Cómo ejecutarlo en tu computadora

1. Clona el repositorio:
   ```bash
   git clone https://github.com/angelcaldasdev/CrecimientoDiario.git
   cd CrecimientoDiario
   ```
2. Abre la carpeta en **Visual Studio Code**.
3. Ejecuta `index.html` con la extensión **Live Server**.

---

## ✍️ Cómo publicar un artículo nuevo

1. Abre `articulos.js`.
2. Copia un bloque `{ ... }` completo y pégalo **al inicio** de la lista `listaDeArticulos`.
3. Cambia sus datos:
   - `titulo`: título del artículo.
   - `categoria`: si escribes una categoría nueva, el filtro se crea solo.
   - `fecha`: formato `AAAA-MM-DD`.
   - `resumen`: una o dos frases que aparecen en la tarjeta.
   - `contenido`: cada texto entre comillas es un párrafo.
4. Guarda y sube los cambios:
   ```bash
   git add .
   git commit -m "Agrego artículo nuevo"
   git push
   ```

---

## 🚀 Publicarlo gratis con GitHub Pages

1. En el repositorio, entra a **Settings → Pages**.
2. En *Source* elige **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
3. Guarda. En uno o dos minutos la web estará en `https://angelcaldasdev.github.io/CrecimientoDiario/`.

---

## 🎯 Objetivo

Compartir lecturas breves que inspiren hábitos positivos y ayuden a crecer
un poco cada día, publicando artículos nuevos con el tiempo.

---

## 📬 Contacto

- **GitHub:** [angelcaldasdev](https://github.com/angelcaldasdev)
- **LinkedIn:** [Ángel Rafael Caldas Ocmín](https://www.linkedin.com/in/angel-rafael-caldas-ocm%C3%ADn-930b1a151)
- **Correo:** [acaldaso05@gmail.com](https://mail.google.com/mail/?view=cm&fs=1&to=acaldaso05@gmail.com)

---

⭐ Si te gustó el proyecto, ¡déjame una estrella en GitHub!