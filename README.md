# 🚀 DevSecOps Pipeline: Exercises & Fundamentals

Este repositorio contiene una serie de ejercicios prácticos para el aprendizaje y la implementación progresiva de pipelines de CI/CD utilizando **GitHub Actions**. El objetivo principal es aplicar buenas prácticas en automatización, gestión de secretos, ejecución condicional y seguridad en el flujo de integración continua.

---

## 🎯 Objetivos
* **Estructura y Sintaxis:** Comprender la jerarquía obligatoria de workflows en GitHub (`.github/workflows/`).
* **Seguridad y Credenciales:** Gestionar de forma segura variables de entorno y **GitHub Secrets** sin exponer información sensible en el código.
* **Lógica de Pipelines:** Implementar condicionales (`if`), filtrado por ramas (`main` vs. desarrollo) y manejo de estados de salida (`exit codes`).

---

## 📂 Contenido del Repositorio

* **`P1.Hola_Mundo/`**: Configuración básica e inicio del primer workflow en GitHub Actions.
* **`Ejercicio 2`**: Control de variables de entorno globales/job-level e inyección segura de secretos (`API_TOKEN`).
* **`Ejercicio 3`**: Ejecución condicional de pasos y filtrado dinámico según la rama objetivo (`main`).

---

## 🛠️ Tecnologías Utilizadas
* **CI/CD:** GitHub Actions
* **Control de Versiones:** Git / GitHub
* **Scripting:** Bash / Linux