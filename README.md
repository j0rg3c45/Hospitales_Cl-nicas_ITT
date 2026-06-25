# 🏥 Hospitales Clínicas ITT

## Propósito

Este módulo forma parte del proyecto de **Gobierno de Datos** y tiene como objetivo principal realizar el análisis geoespacial de hospitales y clínicas del territorio, permitiendo la visualización interactiva, el control por capas y la espacialización de cada institución prestadora de salud (IPS) referente.

El proyecto integra técnicas de ciencia de datos con análisis espacial para generar un **Geovisor interactivo** que facilite la toma de decisiones basada en la ubicación geográfica de las entidades de salud.

---

## 📁 Estructura del Proyecto

```
Hospitales Clínicas ITT/
├── Agente/          → Documentación del rol, contexto y configuración del agente de datos.
├── Notebooks/       → Cuadernos Jupyter (Google Colab) con el pipeline de análisis espacial.
├── Data/            → Datos de entrada: archivos JSON con polígonos/puntos de clínicas y hospitales.
├── Outputs/         → Resultados: mapas exportados (HTML), reportes y entregables finales.
└── README.md        → Este archivo.
```

### 📂 Agente/
Contiene la documentación del rol del Científico de Datos / Data Steward encargado de este módulo, incluyendo contexto operativo, lineamientos de gobernanza y protocolos de calidad de datos.

### 📂 Notebooks/
Cuadernos de análisis preparados para ejecución en **Google Colab**. Incluyen:
- Carga y transformación de datos geográficos.
- Espacialización con GeoPandas.
- Generación del Geovisor interactivo con Folium.
- Control de capas por institución.

### 📂 Data/
Almacena los archivos de entrada del proyecto, principalmente:
- `hospitales_clinicas.json` — Archivo GeoJSON con los polígonos y/o puntos de ubicación de cada clínica y hospital.

### 📂 Outputs/
Resultados generados por el análisis:
- Mapas interactivos exportados en formato HTML.
- Capturas y reportes para presentaciones.
- Entregables para stakeholders.

---

## 🛠️ Tecnologías Utilizadas

| Herramienta | Uso |
|-------------|-----|
| Python 3.x | Lenguaje principal |
| GeoPandas | Procesamiento de datos geoespaciales |
| Folium | Visualización de mapas interactivos |
| Google Colab | Entorno de ejecución en la nube |
| GeoJSON | Formato de datos geográficos |

---

## 🚀 Cómo Ejecutar

1. Abrir el notebook en Google Colab.
2. Asegurarse de que el archivo JSON esté disponible en `Data/`.
3. Ejecutar las celdas secuencialmente.
4. Los mapas generados se exportarán a `Outputs/`.

---

## 📌 Repositorio

🔗 [GitHub - Hospitales_Clínicas_ITT](https://github.com/j0rg3c45/Hospitales_Cl-nicas_ITT.git)

---

## 👤 Autor

Data Steward — Proyecto Gobierno de Datos 2026
