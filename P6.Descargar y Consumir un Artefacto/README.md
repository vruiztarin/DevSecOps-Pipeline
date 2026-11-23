# Ejercicio 6 – Descargar y Consumir un Artefacto
Objetivo del ejercicio:

-Mantener o reutilizar el flujo que genera el artefacto (prueba en resultados/).

-Añadir un segundo job (por ejemplo, consumir-artefacto) que dependa del anterior (needs:) y descargue el artefacto usando la acción oficial actions/download-artifact@v4.

-Comprobar en los logs del segundo job que el fichero descargado existe y conserva su contenido.