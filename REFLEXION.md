# 📝 Reflexión Grupal – Práctica Git Colaborativa

## 1️⃣ ¿Qué ventajas tiene trabajar con ramas?

Trabajar con ramas permite desarrollar funcionalidades de forma aislada sin afectar la rama principal (`main`).  
Esto facilita el trabajo en paralelo entre varios miembros del equipo, reduce el riesgo de errores en producción y permite probar cambios antes de integrarlos definitivamente.

Además, las ramas mejoran la organización del proyecto y permiten mantener un historial más estructurado y comprensible.

---

## 2️⃣ ¿Por qué son útiles los Pull Requests en un equipo?

Los Pull Requests (PR) permiten revisar los cambios antes de fusionarlos en la rama principal.  
Son útiles porque:

- Facilitan la revisión de código entre compañeros.
- Permiten discutir mejoras antes de integrar cambios.
- Detectan conflictos automáticamente.
- Mantienen un control claro de qué cambios se integran y cuándo.

En entornos profesionales, los PR forman parte esencial del flujo de trabajo colaborativo.

---

## 3️⃣ ¿Qué aprendisteis al resolver el conflicto?

Aprendimos que un conflicto ocurre cuando dos ramas modifican la misma línea de un archivo y Git no puede decidir cuál mantener automáticamente.

Durante la resolución:

- Identificamos las marcas de conflicto (`<<<<<<<`, `=======`, `>>>>>>>`).
- Analizamos ambas versiones del cambio.
- Decidimos un título consensuado.
- Eliminamos las marcas manualmente.
- Confirmamos la fusión mediante commit.

Esto nos permitió comprender cómo funciona internamente el proceso de merge y la importancia de sincronizar correctamente las ramas.

---

## 4️⃣ Dificultades encontradas durante la práctica

- Entender cuándo era necesario hacer `pull` antes de trabajar.
- Resolver correctamente el conflicto sin dejar marcas en el archivo.
- Gestionar el orden correcto de los comandos (`add`, `commit`, `push`).
- Comprender la diferencia entre repositorio local y remoto.

---

## 📌 Conclusión

La práctica permitió comprender el flujo real de trabajo con Git en equipo: desarrollo en paralelo mediante ramas, revisión con Pull Requests y resolución manual de conflictos antes de integrar cambios en `main`.

Se ha adquirido una visión práctica del trabajo colaborativo en proyectos de desarrollo.