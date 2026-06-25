# Hospitales Clinicas ITT

## Proposito

Este modulo forma parte del proyecto de **Gobierno de Datos** y tiene como objetivo principal realizar el analisis geoespacial de hospitales y clinicas del territorio, permitiendo la visualizacion interactiva, el control por capas y la espacializacion de cada institucion prestadora de salud (IPS) referente.

El proyecto integra tecnicas de ciencia de datos con analisis espacial para generar un **Geovisor interactivo** que facilite la toma de decisiones basada en la ubicacion geografica de las entidades de salud.

---

## Estructura del Proyecto

```
Hospitales Clinicas ITT/
├── Agente/          -> Documentacion del rol, contexto y configuracion del agente de datos.
├── Notebooks/       -> Cuadernos Jupyter (Google Colab) con el pipeline de analisis espacial.
├── Data/            -> Datos de entrada: archivos JSON con poligonos/puntos de clinicas y hospitales.
├── Outputs/         -> Resultados: mapas exportados (HTML), reportes y entregables finales.
└── README.md        -> Este archivo.
```

### Agente/

Contiene la documentacion del rol del Cientifico de Datos / Data Steward encargado de este modulo, incluyendo contexto operativo, lineamientos de gobernanza y protocolos de calidad de datos.

### Notebooks/

Cuadernos de analisis preparados para ejecucion en **Google Colab**. Incluyen:

- Carga y transformacion de datos geograficos.
- Espacializacion con GeoPandas.
- Generacion del Geovisor interactivo con Folium.
- Control de capas por institucion.

### Data/

Almacena los archivos de entrada del proyecto, principalmente:

- `hospitales_clinicas.json` — Archivo GeoJSON con los poligonos y/o puntos de ubicacion de cada clinica y hospital.

### Outputs/

Resultados generados por el analisis:

- Mapas interactivos exportados en formato HTML.
- Capturas y reportes para presentaciones.
- Entregables para stakeholders.

---

## Tecnologias Utilizadas

| Herramienta | Uso |
|-------------|-----|
| Python 3.x | Lenguaje principal |
| uv | Gestor de paquetes y entornos virtuales |
| GeoPandas | Procesamiento de datos geoespaciales |
| Folium | Visualizacion de mapas interactivos |
| Google Colab | Entorno de ejecucion en la nube |
| GeoJSON | Formato de datos geograficos |

---

## Como Ejecutar

1. Abrir el notebook en Google Colab.
2. Asegurarse de que el archivo JSON este disponible en `Data/`.
3. Ejecutar las celdas secuencialmente.
4. Los mapas generados se exportaran a `Outputs/`.

Para ejecucion local con uv:

```bash
uv venv
uv pip install geopandas folium mapclassify
```

---

## Repositorio

[GitHub - Hospitales Clinicas ITT](https://github.com/j0rg3c45/Hospitales_Cl-nicas_ITT.git)

---

## Autor

Data Steward — Proyecto Gobierno de Datos 2026
