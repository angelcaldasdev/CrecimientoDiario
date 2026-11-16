# Crecimiento Diario 🌅

### 🔗 [**Visitar la web → angelcaldasdev.github.io/crecimiento-diario**](https://angelcaldasdev.github.io/crecimiento-diario/)

Página web de **crecimiento personal** con artículos cortos sobre hábitos, disciplina, constancia, perseverancia y mentalidad. Está pensada para inspirar y motivar con lecturas breves que se pueden terminar en pocos minutos.

## Contenido

- **Franja superior** con una frase motivadora.
- **Portada** con un mensaje de bienvenida.
- **Artículos** en tarjetas, con **filtros por categoría**. Las categorías se crean solas a partir de los artículos.
- **Ventana de lectura**: al abrir un artículo se muestra completo, sin salir de la página.
- **Pie de página** con enlaces.

## Tecnologías

- HTML5
- CSS3 (diseño responsive y variables CSS)
- JavaScript (sin librerías)

## Estructura del proyecto

```
CrecimientoDiario/
├── index.html      # Estructura de la página
├── style.css       # Estilos
├── funciones.js    # Lógica: tarjetas, filtros y ventana de lectura
├── articulos.js    # Lista de artículos (aquí se publica contenido nuevo)
└── README.md
```

## Cómo ejecutarlo en local

1. Clona el repositorio:
   ```bash
   git clone https://github.com/angelcaldasdev/crecimiento-diario.git
   ```
2. Ábrelo en VS Code.
3. Instala la extensión **Live Server**, haz clic derecho en `index.html` y elige **Open with Live Server**.

## Cómo publicar un artículo nuevo

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

## Categorías actuales

Perseverancia · Hábitos · Mentalidad · Productividad · Disciplina · Constancia · Trabajo duro

## Publicarlo gratis con GitHub Pages

1. En el repositorio, entra a **Settings → Pages**.
2. En *Source* elige **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
3. Guarda. En uno o dos minutos la web estará en `https://angelcaldasdev.github.io/crecimiento-diario/`.



## Autor

**Angel Caldas** · Lima, Perú