# Ejercicio 5 – Compilación y Gestión de Artefactos
En un flujo DevSecOps real, el pipeline no solo analiza el código, sino que lo compila o empaqueta (un binario, una imagen de Docker, un .zip o los archivos minificados de una web) y guarda el resultado para que pueda ser desplegado o probado en pasos posteriores.

# Objetivo del ejercicio:
Simular la generación de un artefacto: Crear un paso que genere un fichero local en la máquina virtual del runner (por ejemplo, build/app-v1.zip o un informe security-report.txt).

Persistir el resultado (upload-artifact): Utilizar la acción oficial de GitHub Actions (actions/upload-artifact@v4) para guardar ese fichero como un artefacto descargable desde la propia interfaz de GitHub.