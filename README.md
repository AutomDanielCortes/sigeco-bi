# SIGECO BI · Proyecto aplicado I · ESEIT

Responsable: Daniel Stiven Cortes Pedreros  
Docente: Cesar Augusto Espinosa Vargas  
Empresa: Comercializadora Horizonte S.A.S. (ficticia)

## Alcance

Wiki académica con las tres fases del proyecto, cuatro componentes de planeación, cuatro de ejecución, un tablero interactivo de demostración, anexos en PDF/Excel, diagramas y datos sintéticos.

## Publicación

Publica el **contenido** de esta carpeta en la raíz de la rama `main` del repositorio GitHub `AutomDanielCortes/sigeco-bi`. En **Settings → Pages**, usa `Deploy from a branch`, rama `main`, carpeta `/ (root)`. No subas únicamente el ZIP.

## Consideraciones metodológicas

- El proyecto y los actores organizacionales son ficticios.
- La Fase 1 conserva los datos académicos del estudiante; la Fase 2, Fase 3 y el ROI presentan un escenario estimado/documentado, no registros de ejecución empresarial.
- Los 180 registros del tablero son **sintéticos**, no son datos extraídos de Microsoft Financial Sample; su fuente es `datos/ventas_sinteticas_sigeco.csv`.
- Microsoft Financial Sample se cita como fuente independiente de referencia para una implementación en Power BI.
- El proyecto incluye un prototipo **web** funcional, no un archivo Power BI `.pbix`.

## Archivos

- `index.html`, `styles.css`, `app.js`: Wiki web.
- `datos/ventas_demo.js`: datos sintéticos para uso sin servidor.
- `datos/ventas_sinteticas_sigeco.csv`: los mismos registros en CSV.
- `documentos/Acta_SIGECO_BI.pdf`: Acta Fase 1.
- `documentos/Informe_Final_SIGECO_BI.pdf`: fases 2/3 e impacto.
- `documentos/Plan_SIGECO_BI.xlsx`: cronograma, presupuesto, riesgos y ROI editables.
- `assets/edt_wbs.svg`, `assets/cronograma_gantt.svg`: diagramas.

Abre `index.html` localmente para probar el sitio sin conexión. Comprueba todos los enlaces de anexos tras publicar en GitHub Pages.
