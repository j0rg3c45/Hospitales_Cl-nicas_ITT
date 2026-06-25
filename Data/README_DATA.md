# 📂 Data

En esta carpeta se almacena el archivo principal de entrada:

## Archivo esperado

- **`hospitales_clinicas.json`** — Archivo en formato GeoJSON que contiene los polígonos y/o puntos de ubicación de cada hospital y clínica del territorio.

## Estructura esperada del GeoJSON

```json
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "nombre": "Nombre de la Institución",
        "tipo": "Hospital | Clínica | IPS",
        "direccion": "Dirección física",
        "municipio": "Municipio"
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [[[lon, lat], [lon, lat], ...]]
      }
    }
  ]
}
```

## Notas

- El CRS debe ser **EPSG:4326** (WGS84).
- El campo `nombre` es obligatorio para la generación del control de capas en el Geovisor.
- Los tipos de geometría aceptados son: `Point`, `Polygon`, `MultiPolygon`.
