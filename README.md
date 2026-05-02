# 🛒 Mercado El Paisa — Cárnicos & Abarrotes

Sitio web desarrollado como proyecto práctico del **Taller de GitHub** — Desarrollo web con Git, GitHub y GitHub Pages.

---

## 🌐 Sitio publicado

🔗 **https://TU-USUARIO.github.io/carnicos-abarrotes/**

> Reemplaza `TU-USUARIO` con tu nombre de usuario de GitHub una vez actives GitHub Pages.

---

## 📋 Descripción del proyecto

Sitio web para **Mercado El Paisa**, una empresa familiar antioqueña con 15 años de experiencia en la venta de cárnicos y abarrotes en Bogotá. El proyecto fue desarrollado aplicando el flujo profesional de trabajo con Git y GitHub: creación de repositorio, trabajo en ramas, pull requests y publicación con GitHub Pages.

El sitio cuenta con tres páginas principales:

- **Inicio** — Presentación del negocio, propuesta de valor y llamados a la acción
- **Productos** — Catálogo de cárnicos y abarrotes con precios y etiquetas
- **Contacto** — Información de contacto, horarios y formulario de pedido

---

## 📁 Estructura del repositorio

```
carnicos-abarrotes/
├── index.html          → Página principal (inicio)
├── productos.html      → Catálogo de productos
├── contacto.html       → Información y formulario de contacto
├── css/
│   └── estilos.css     → Hoja de estilos global del sitio
└── README.md           → Documentación del proyecto
```

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica de las páginas |
| CSS3 | Estilos, animaciones, diseño dark mode y responsive |
| Google Fonts | Tipografías Bebas Neue y Nunito |
| Git | Control de versiones local |
| GitHub | Repositorio remoto y colaboración |
| GitHub Pages | Despliegue y publicación del sitio web |

---

## 🔀 Flujo de trabajo Git aplicado

### 1. Configuración inicial
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

### 2. Creación del repositorio
- Repositorio creado desde **github.com**
- Inicializado con archivo `README.md`
- Visibilidad: **Público**

### 3. Estructura de archivos
Los archivos fueron creados directamente desde la interfaz web de GitHub:

| Archivo | Descripción |
|---|---|
| `index.html` | Página de inicio con hero, ticker animado y sección de propuesta |
| `productos.html` | Catálogo con 12 productos divididos en cárnicos y abarrotes |
| `contacto.html` | Tarjetas de contacto, horario y formulario |
| `css/estilos.css` | Hoja de estilos completa con tema oscuro (dark mode) |

### 4. Rama de trabajo
Se creó la rama `feature/catalogo` para desarrollar el catálogo de productos de manera independiente sin afectar la rama principal:

```
main
 └── feature/catalogo  ← desarrollo del catálogo de productos
```

**Commits realizados en la rama:**
- `Add product catalog for meats and groceries`
- `Add initial HTML structure for the website`
- `Add contacto.html for contact information and form`
- `Add CSS styles for layout and components`

### 5. Pull Request
- PR creado desde `feature/catalogo` → `main`
- Revisión de archivos cambiados en la pestaña *Files changed*
- Estado: **Merged** ✅

### 6. Publicación con GitHub Pages

**Pasos para activar:**
1. Ir a **Settings → Pages**
2. En *Source* seleccionar **main branch** y carpeta `/root`
3. Clic en **Save**
4. Esperar ~1 minuto

Cada `git push` a `main` actualiza el sitio automáticamente.

---

## 🎨 Diseño del sitio

El sitio fue diseñado con una estética **dark mode** moderna y llamativa:

- **Paleta de colores** — Fondo negro `#0f0f0f`, acento verde `#22c55e`, texto gris `#a1a1aa`
- **Tipografía** — Bebas Neue (títulos bold) + Nunito (cuerpo legible)
- **Efectos** — Ticker animado en verde, tarjetas flotantes en el hero, hover con borde verde
- **Responsive** — Adaptado para móvil y escritorio
- **Componentes destacados:**
  - Header sticky con blur
  - Texto de fondo gigante decorativo ("FRESCO")
  - Ticker animado con scroll infinito
  - Cards de productos con etiqueta "Popular"
  - Panel de contacto con tarjetas individuales por dato

---

## 📄 Páginas del sitio

### `index.html` — Inicio
- Hero con titular en Bebas Neue y tarjetas flotantes animadas
- Ticker animado en verde con datos del negocio
- Sección de propuesta de valor con 4 cards
- Banner CTA verde de contacto

### `productos.html` — Catálogo

**Cárnicos:**

| Producto | Precio |
|---|---|
| Pechuga de pollo | $6.500 / lb |
| Lomo de res ⭐ | $14.000 / lb |
| Costilla de cerdo | $9.000 / lb |
| Carne molida | $8.500 / lb |
| Chuleta de res | $12.000 / lb |
| Chorizo paisa | $7.000 / lb |

**Abarrotes:**

| Producto | Precio |
|---|---|
| Arroz Diana x 500g | $3.200 |
| Aceite vegetal x 1L | $8.900 |
| Fríjoles x 500g ⭐ | $4.500 |
| Panela x 500g | $2.800 |
| Huevos x 12 und | $9.500 |
| Leche entera x 1L | $3.400 |

### `contacto.html` — Contacto
- Tarjetas individuales por dato de contacto (teléfono, WhatsApp, email, dirección)
- Tabla de horarios con indicador de día cerrado
- Formulario con campos: nombre, teléfono, correo, tipo de pedido y mensaje

---

## ⚙️ Referencia de comandos Git utilizados

| Comando | Acción |
|---|---|
| `git config --global user.name` | Configura el nombre del autor |
| `git clone <url>` | Clona el repositorio localmente |
| `git add .` | Agrega todos los cambios al área de staging |
| `git commit -m "mensaje"` | Guarda un snapshot con mensaje descriptivo |
| `git push origin main` | Sube los commits al repositorio remoto |
| `git checkout -b feature/catalogo` | Crea y cambia a una nueva rama |
| `git push origin feature/catalogo` | Sube la rama al repositorio remoto |
| `git status` | Muestra el estado actual de los archivos |
| `git log --oneline` | Historial de commits en formato corto |

---

## 👤 Autor

**Tu nombre aquí**
- GitHub: [@tu-usuario](https://github.com/tu-usuario)
- Repositorio: [carnicos-abarrotes](https://github.com/tu-usuario/carnicos-abarrotes)

---

## 📚 Recursos del taller

- Documentación oficial de GitHub: [docs.github.com](https://docs.github.com)
- GitHub Skills (cursos interactivos): [skills.github.com](https://skills.github.com)
- Guía de Markdown para README: [markdownguide.org](https://markdownguide.org)
- GitHub Actions para automatizar deploys

---

*Proyecto desarrollado en el Taller Práctico de GitHub — Nivel Principiante–Intermedio · Duración 2 horas*
