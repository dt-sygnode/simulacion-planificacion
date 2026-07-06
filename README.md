# simulacion-planificacion
Simulación CLIENTE-EX: $1.328M en OTs ejecutadas sin firma ni factura pese a meta global cumplida.

# SYGNODE — Informe de Estado Semanal (Simulación)

Plantilla de informe de decisión operativa, diseñada por SYGNODE para ilustrar el formato de reporte semanal que entrega su sustema nervioso empresarial.

> ⚠️ **Este repositorio contiene datos 100% ficticios.** "CLIENTE-EX", las OTs, montos, fechas y hallazgos son una simulación con fines de demostración. No corresponden a ningún cliente real de SYGNODE.

## Qué es esto

Un informe que simula la lectura semanal que SYGNODE entrega a un cliente industrial: estado de facturación, compuertas de conversión (ejecución → evidencia → firma → factura), mapa de presión, cola de decisiones priorizadas y anexos de evidencia.

Pensado para verse tanto en pantalla (scroll, animaciones de entrada) como impreso/exportado a PDF (una sección por página, a sangre completa).

## Uso

Clona el repo y abre el archivo directamente en el navegador:

```bash
git clone <url-de-este-repo>
cd <carpeta>
open SYGNODE_CLIENTE-EX_Informe.html   # o doble clic
```

Para exportar a PDF: `Cmd/Ctrl + P` → Destino: Guardar como PDF → Márgenes: Ninguno → Gráficos de fondo: activado.

## Estructura

- Documento único, sin build ni dependencias externas (salvo Google Fonts vía CDN).
- 14 secciones (`<section class="slide">`), cada una diseñada para ocupar exactamente una página impresa.
- CSS con media query `@media print` separada del estilo de pantalla.

## Licencia / uso

Sin licencia de código abierto asignada. Este material es propiedad de SYGNODE (Compro Chile SpA) y se comparte con fines de demostración interna. No reutilizar el diseño, la marca ni el contenido sin autorización.
