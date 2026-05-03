# 🗺️ Mapa de Centros de Datos en EE.UU.

Mapa coroplético interactivo que muestra la distribución de centros de datos en los Estados Unidos, clasificados según su estado operacional.

> **Con casi el 40% del total mundial, EE.UU. es el país con más centros de datos del mundo.**
> Datos disponibles hasta abril de 2026.

---

## 📊 Descripción general

Este proyecto visualiza las instalaciones de centros de datos en los 50 estados de EE.UU. más el Distrito de Columbia, desglosadas en tres categorías:

| Categoría | Descripción |
|---|---|
| 🟦 **En funcionamiento** | Activos y operativos actualmente |
| 🔵 **En construcción** | En proceso de edificación al momento de los datos |
| 🩵 **Planificados** | Anunciados o aprobados, aún no construidos |

---

## ✨ Funcionalidades

- **Mapa coroplético interactivo** — Coloreado según el número de instalaciones por estado
- **Botones de filtro** — Alterna entre Total, En funcionamiento, En construcción y Planificados
- **Estados clicables** — Selecciona un estado para resaltarlo en el mapa y en el gráfico de barras
- **Gráfico de barras** — Ranking de todos los estados con segmentos apilados por categoría
- **Tooltips** — Pasa el cursor sobre cualquier estado para ver los datos exactos
- **Anotaciones contextuales** — Datos clave mostrados directamente sobre el mapa según la vista activa

---

## 🏆 Datos destacados

- **Virginia** lidera con **599 instalaciones en total** (340 operacionales, 68 en construcción, 191 planificadas)
- **Texas** ocupa el segundo lugar con **438 instalaciones** (258 operacionales, 50 en construcción, 130 planificadas)
- **California** es tercera con **287 instalaciones**, la mayoría ya operacionales (236)
- **Montana** lidera en ratio planificados/activos: **4.4x** — 22 planificados con solo 5 operacionales
- **19 estados** no tienen ningún centro de datos actualmente en construcción

---

## 🛠️ Tecnologías utilizadas

- [D3.js v7](https://d3js.org/) — Renderizado del mapa y visualización de datos
- [TopoJSON v3](https://github.com/topojson/topojson) — Datos geográficos de EE.UU.
- HTML, CSS y JavaScript puro — Sin herramientas de compilación necesarias

---

## 🚀 Uso

No requiere instalación. Abre el archivo directamente en cualquier navegador moderno:

```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/nombre-repositorio.git

# Abre el mapa
open index.html
```

O simplemente haz doble clic sobre `index.html` para abrirlo en local.

---

## 📁 Estructura del proyecto

```
.
└── index.html      # Aplicación del mapa (archivo único autocontenido)
```

---

## 📦 Datos

El conjunto de datos cubre **52 jurisdicciones** (50 estados + Washington D.C.) e incluye:

- `facilities` — Total de centros de datos
- `facilities_operational` — Actualmente operacionales
- `facilities_underconstruction` — En construcción
- `facilities_planned` — Planificados

**Fuente:** [Data Center Map](https://www.datacentermap.com/)

---

## 📄 Licencia

Este proyecto tiene fines informativos y educativos. Datos obtenidos de Data Center Map.
