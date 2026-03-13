# CV – Eliezer David Salazar

CV profesional como sitio web estático (HTML/CSS), desplegado en GitHub Pages.

🔗 **Demo en vivo:** https://babinobass.github.io/cv/

---

## Visualizar localmente

1. Clona o descarga este repositorio.
2. Abrí el archivo `index.html` directamente en tu navegador (doble clic o arrástralo a la ventana del navegador).

No se requiere ningún servidor ni dependencias.

---

## Desplegar en GitHub Pages

1. Ve a **Settings** del repositorio en GitHub.
2. En el menú lateral, hacé clic en **Pages**.
3. En **Source**, seleccioná **Deploy from a branch**.
4. Elegí la rama **main** y la carpeta **/ (root)**.
5. Hacé clic en **Save**.

En unos minutos el CV estará disponible en:
```
https://<tu-usuario>.github.io/<nombre-del-repo>/
```

---

## Exportar a PDF desde el navegador

1. Abrí el CV en tu navegador (localmente o desde GitHub Pages).
2. Presioná **Ctrl + P** (Windows/Linux) o **Cmd + P** (Mac) para imprimir.
3. En el destino de impresión, seleccioná **"Guardar como PDF"**.
4. Orientación: **Vertical (Portrait)**, tamaño **A4**.
5. Hacé clic en **Guardar**.

El diseño incluye estilos `@media print` optimizados para A4, por lo que el resultado será limpio y profesional.

---

## Estructura del proyecto

```
.
├── index.html   # CV completo (HTML semántico)
├── styles.css   # Estilos (layout de dos columnas, responsive, print)
└── README.md    # Este archivo
```
