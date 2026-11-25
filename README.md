# FSD-1984 · Progreso de QA

Filtrado de textos de Android por contactos de compañía. [Ver ticket en Jira](https://firmscribe.atlassian.net/browse/FSD-1984).

**Corte del 25 de noviembre de 2026.** 10 casos diseñados, 0 ejecutados y 10 por ejecutar. Build de staging por confirmar.

[Descargar el tablero HTML bilingüe](FSD-1984-dashboard-QA.html) y abrirlo en el navegador para buscar, filtrar y desplegar los casos. También está disponible el [tablero PDF](FSD-1984-dashboard-QA.pdf).

| Caso | Escenario | Estado |
| --- | --- | --- |
| TC_01 | **Happy Path.** Archivar solo el SMS del contacto listado y comprobar el conteo | Por ejecutar |
| TC_02 | Archivar el SMS del segundo número de un contacto de compañía | Por ejecutar |
| TC_03 | Archivar el SMS de un contacto que se muestra en formato nacional en Android | Por ejecutar |
| TC_04 | Archivar el MMS grupal con un participante listado | Por ejecutar |
| TC_05 | Excluir el SMS saliente hacia un número no listado | Por ejecutar |
| TC_06 | Excluir el texto y la foto del MMS de un remitente no listado | Por ejecutar |
| TC_07 | Archivar el SMS no listado con la sincronización desactivada | Por ejecutar |
| TC_08 | Excluir textos Android con sincronización activa y lista de compañía vacía | Por ejecutar |
| TC_09 | Conservar la captura Mac mientras el filtro Android está activo | Por ejecutar |
| TC_10 | Validar coincidencias exactas por correo si el flujo Android admite ese dato | Por ejecutar |
