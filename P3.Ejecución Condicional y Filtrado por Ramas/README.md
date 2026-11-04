# Ejercicio 3: Ejecución Condicional y Filtrado por Ramas

# Contexto:
    En un entorno real de DevSecOps, nunca aplicas las mismas reglas ni ejecutas las mismas tareas en una rama de pruebas o desarrollo que en la rama principal de producción (main). Necesitas que el pipeline sea inteligente y tome decisiones según dónde esté corriendo el código.

# Objetivos del ejercicio:

    1.Filtrar por rama: Configurar el pipeline para que se active ante cualquier push, pero que identifique en qué rama se encuentra.

    2.Pasos condicionales (if): Crear un pipeline con varios pasos, donde uno de ellos solo se ejecute si la rama activa es main, y se salte (o falle de forma controlada) si estás en otra rama.

# Lo que debes investigar y aplicar en tu nuevo archivo ejercicio3.yml:

    Busca cómo utilizar el contexto de GitHub Actions para evaluar la referencia de la rama actual (por ejemplo, investiga cómo se usa github.ref o el filtro de ramas a nivel de trigger).

    Añade la directiva if: dentro de un paso para condicionar su ejecución basándote en si estás en la rama main.

    Diseña un paso que imprima "Ejecutando validación estricta de producción" solo si se cumple la condición de la rama, y otro paso genérico que se ejecute siempre.