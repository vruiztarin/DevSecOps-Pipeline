# Ejercicio 4 - Integración de Linter y Verificación de Código
# ¿De qué trata?
En un entorno real, antes de desplegar nada, el pipeline debe comprobar automáticamente que el código o los ficheros de configuración no tienen errores de sintaxis.

# Objetivos del ejercicio:
    -Añadir un paso previo que analice la calidad o sintaxis de tus ficheros YAML antes de dar el visto bueno.
    -Utilizar una acción oficial de la comunidad de GitHub Marketplace (por ejemplo, una herramienta para validar sintaxis de YAML o un linter).
    -Hacer que el pipeline falle (exit 1) automáticamente si encuentra un error de formato en el código.