# Herramienta de automatización · KAM

Demostración académica del Equipo 01 (Seminario de Titulación · Inteligencia Artificial y Automatización de Flujos de Trabajo para Negocios).

La página simula la descarga de reportes comerciales desde los portales de proveedores de cada cliente
(Suburbia, Sears y Chedraui). No se conecta a ningún portal: usa el último reporte guardado junto a esta página.

**Cómo usarla:** elige el cliente, elige qué quieres descargar y pulsa **Ejecutar**.

- **Base de datos:** descarga el archivo tal como lo entrega el portal (CSV o XML).
- **Reporte comercial:** lee la base, calcula indicadores, rankings y hallazgos, y descarga un PDF.
- **Ambos:** descarga la base de datos y el reporte comercial en PDF.

**Encuesta de servicio:** al terminar cada descarga aparece la encuesta (Google Forms) con el folio y los datos de la
descarga ya llenos. Cada respuesta llega al Control de Solicitudes (Google Sheets) y se registra en Baserow mediante
Apps Script. Si la encuesta indica que el portal no funcionó o que hubo un error, el equipo recibe un aviso por correo.

Todo corre en el navegador de quien abre la página: no requiere instalar nada ni iniciar sesión.
El generador de PDF (html2pdf.js, licencia MIT) viene incluido en el repositorio.

**Datos anonimizados:** se cambiaron los nombres y claves de tiendas y del proveedor, se alteraron piezas e importes
y se quitaron costos, márgenes y utilidades. Ningún archivo contiene información real de ventas.
