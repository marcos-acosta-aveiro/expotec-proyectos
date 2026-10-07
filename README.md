# Proyectos Expotec

Proyectos académicos de Marcos Adrián Acosta Aveiro, estudiante técnico en Informática del Colegio Salesianito.

## Expotec 2026 — SentinelX

Prototipo de detección y alerta con ESP32, sensores MQ-2 y DHT22, buzzer y LED. El trabajo informado incluye firmware C++, muestreo no bloqueante, doble lectura de sensores, panel web y alertas por correo mediante Webhook.

Archivos disponibles en este repositorio:

- `sentinelx-dashboard.html`: panel web original localizado en la carpeta del proyecto. Usa Chart.js desde un CDN y conserva una dirección de dispositivo de ejemplo (`192.168.1.X`); esa dirección requiere configuración para conectarse a un ESP32.
- `sentinelx-triptico.pdf`: material de presentación del proyecto.
- `expotec-2025-supermercado.md`: descripción del sistema de gestión comercial.

El firmware ESP32 no está incluido: no se localizó un archivo fuente correspondiente durante esta preparación. La descripción no constituye verificación de funcionamiento con hardware ni certificación de seguridad contra incendios.

## Expotec 2025 — Gestión de supermercado

Sistema académico basado en Microsoft Excel y VBA, con planillas relacionadas para catálogo de artículos, inventario y ventas, macros de automatización y formularios de validación.

La planilla original existe, pero contiene hojas de usuarios y registros de personas. No se incluye en esta primera carga; queda pendiente preparar una copia demostrativa sin credenciales ni datos personales y revisar sus macros.

## Uso

Descargar el HTML y abrirlo en el navegador para revisar el panel. Para obtener datos del dispositivo se requiere configurar el endpoint y disponer del hardware correspondiente. La librería Chart.js requiere conexión a internet.

Estos son proyectos académicos. No se presentan como productos certificados o sistemas comerciales en producción. No se ha elegido una licencia del proyecto.
