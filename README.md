# CV – Eliezer David Salazar

CV profesional de **Eliezer David Salazar**, Front-End Developer Semi Senior, construido como sitio web estático (HTML/CSS puro) listo para desplegarse en **GitHub Pages** y exportarse a **PDF**.

---

## 🌐 Ver el CV en línea

Una vez desplegado en GitHub Pages, el CV estará disponible en:

```
https://babinobass.github.io/cv/
```

---

## 💻 Visualizar localmente

No se requiere ningún servidor. Simplemente abrí el archivo `index.html` en tu navegador:

```bash
# Opción 1 – abrir directamente
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows

# Opción 2 – servidor local con Python (recomendado)
python3 -m http.server 8000
# Luego abrí http://localhost:8000 en el navegador
```

---

## 🚀 Desplegar en GitHub Pages

1. Ir a **Settings** del repositorio en GitHub.
2. En el menú lateral, hacer clic en **Pages**.
3. En **Source**, seleccionar **Deploy from a branch**.
4. Elegir la rama **`main`** y la carpeta **`/ (root)`**.
5. Hacer clic en **Save**.
6. En unos segundos el CV estará disponible en `https://babinobass.github.io/cv/`.

---

## 📄 Exportar a PDF

1. Abrí el CV en el navegador (localmente o desde GitHub Pages).
2. Presioná **`Ctrl + P`** (Windows/Linux) o **`Cmd + P`** (macOS).
3. Seleccioná **"Guardar como PDF"** (o "Save as PDF") como destino de impresión.
4. En **Más configuraciones**, asegurate de:
   - Tamaño de papel: **A4**
   - Márgenes: **Ninguno** (None)
   - Escala: **100 %** (o "Ajustar al área de impresión")
   - Activar **"Gráficos de fondo"** (Background graphics) para preservar los colores del sidebar.
5. Hacer clic en **Guardar**.

---

## 🛠️ Estructura del proyecto

```
cv/
├── index.html   # CV completo (estructura HTML)
├── styles.css   # Estilos del CV (responsive + print)
└── README.md    # Este archivo
```

---

## ✨ Tecnologías utilizadas

- **HTML5** semántico (`lang="es"`, meta tags, ARIA labels)
- **CSS3** puro — sin JavaScript, sin frameworks
- **Google Fonts** – Inter
- **Font Awesome 6** – iconos de contacto
- `@media print` optimizado para A4
