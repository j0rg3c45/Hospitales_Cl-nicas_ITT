# Estilo de comunicacion y codigo

## Reglas

- No usar emojis en ningun contexto: ni en codigo, comentarios, documentacion, nombres de capas, mensajes de commit, ni en respuestas al usuario.
- Mantener un tono profesional y directo.

## Entorno del usuario

- El usuario tiene instalado **uv** (gestor de paquetes Python de Astral). Usar `uv` y `uvx` como herramienta preferida para instalar dependencias, crear entornos virtuales y ejecutar servidores MCP.
- No es necesario instalar uv; ya esta disponible en el PATH del sistema.

## Notas del dominio (Infraestructura hospitalaria)

- La **categoria** de un centro medico es su nivel de complejidad: Baja, Media o Alta.
- Se diferencian por los servicios prestados y la capacidad instalada.
- Un **Centro de Salud** es de mayor prestacion y portafolio que un Puesto de Salud.
- Jerarquia: Puesto de Salud < Centro de Salud < Hospital.

## Visualizacion

- Usar la paleta de colores de **Paul Tol** o **IBM Design** para graficos y mapas.
- Paul Tol (bright): #4477AA, #EE6677, #228833, #CCBB44, #66CCEE, #AA3377, #BBBBBB
- IBM Design: #648FFF, #785EF0, #DC267F, #FE6100, #FFB000
- Estas paletas son accesibles para daltonismo y se ven bien en impresion.
- En el geovisor, los marcadores se colorean por ESE (no por estado):
  - ESE Centro = Azul
  - ESE Ladera = Verde
  - ESE Norte = Naranja
  - ESE Oriente = Rojo
  - ESE Suroriente = Morado oscuro
- Los 3 puntos de estudio van en morado con icono de estrella.
- Los poligonos de terrenos van con contorno rojo delgado, sin relleno.
