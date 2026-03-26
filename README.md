# 🦐 Recetario Malanga

Recetario web interno del restaurante **Malanga** — 306 recetas organizadas por familias, listo para GitHub Pages.

## 📂 Estructura

```
recetario-malanga/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos completos
├── js/
│   ├── app.js          # Lógica central y configuración
│   └── index.js        # JS de la página principal
├── data/
│   └── recipes.json    # Base de datos de recetas (306 recetas)
└── pages/
    ├── familias.html   # Lista de todas las familias
    ├── familia.html    # Recetas de una familia
    ├── receta.html     # Detalle de una receta
    └── buscar.html     # Búsqueda global
```

## 🚀 Despliegue en GitHub Pages

1. **Sube los archivos** a un repositorio de GitHub
2. Ve a **Settings → Pages**
3. En "Source" selecciona la rama `main` y carpeta `/ (root)`
4. Guarda y espera unos minutos — el sitio estará disponible en `https://tuusuario.github.io/recetario-malanga`

## 📋 Familias incluidas

### 🍽️ Cocina (14 familias)
- Entradas (17 recetas)
- Los Arrebatos del Chef (5 recetas)
- Fuertes Mar (14 recetas)
- Fuertes Tierra (8 recetas)
- Fuertes Mar y Tierra (6 recetas)
- Arroces (7 recetas)
- Langostinos (3 recetas)
- Ceviches (5 recetas)
- Ensaladas (2 recetas)
- Postres (18 recetas)
- Brunch
- Menú Infantil (3 recetas)
- Evento (3 recetas)

### 🍹 Cocteles & Bebidas (11 familias)
- Cocteles Malanga (17 recetas)
- Cocteles Tradicionales (27 recetas)
- Mocktails (4 recetas)
- Sangrias (11 recetas)
- Sodas (5 recetas)
- Jugos Naturales (5 recetas)
- Aromáticas (3 recetas)
- Bebidas (9 recetas)
- Mezcladores (5 recetas)
- Refajo (1 receta)

### 🥃 Licores & Spirits
- Aguardiente, Tequila, Mezcal, Ginebra, Vodka, Ron, Whisky, Maltas, Cervezas

### 🍷 Vinos & Espumosos
- Vino Tinto, Vino Blanco, Vino Rosado, Champañas y Espumosos

## ✨ Características
- Búsqueda en tiempo real por nombre, familia e ingrediente
- Navegación entre recetas (anterior / siguiente)
- Precio carta y costo de receta por plato
- Cálculo de margen de rentabilidad
- Diseño responsivo (desktop y móvil)
- Sin dependencias externas (solo Google Fonts)
- Funciona como sitio estático en GitHub Pages

## 🛠️ Desarrollo local

No necesitas servidor — simplemente abre `index.html` en tu navegador. Para un entorno de desarrollo más completo:

```bash
# Con Python
python3 -m http.server 8080

# Con Node
npx serve .
```

Luego visita `http://localhost:8080`.

---

*Uso exclusivo del equipo de Malanga Restaurante*
