# git-hubFundationClase5
Educativo y de Aprendizaje Personal Javascript

# ¿Qué es un *Issue* en GitHub?

Un **issue** (o "incidencia") en GitHub es una herramienta para **reportar errores, proponer mejoras o hacer preguntas** relacionadas con un repositorio. Es una parte esencial para la **gestión de proyectos y la colaboración en equipo**.

## 🛠 ¿Para qué se usa?

- Reportar **bugs** (errores en el código).
- Sugerir **nuevas funcionalidades** o mejoras.
- Hacer **preguntas** técnicas o de uso del proyecto.
- Llevar un **seguimiento** del trabajo pendiente.
- Asignar tareas a miembros del equipo.

## 🧩 Estructura de un Issue

Un issue puede incluir:

- **Título** descriptivo.
- **Descripción** detallada del problema o sugerencia.
- **Etiquetas** (labels) como `bug`, `enhancement`, `question`, etc.
- **Asignados** (assignees) para indicar quién lo resolverá.
- **Comentarios** para discutir con otros colaboradores.
- **Checklists** para dividir tareas grandes.

## ✅ Ejemplo de Issue

```markdown
### Título: Error al hacer clic en el botón "Enviar"

**Descripción:**
Cuando se hace clic en el botón "Enviar", no ocurre nada. Se espera que el formulario se envíe correctamente.

**Pasos para reproducir:**
1. Ir a la página de contacto.
2. Completar el formulario.
3. Hacer clic en "Enviar".

**Comportamiento esperado:**
El formulario debería enviarse y mostrar un mensaje de éxito.

**Captura de pantalla:**
![bug screenshot](https://ejemplo.com/captura.png)

**Etiquetas:** `bug`, `frontend`

# 🤝 ¿Qué es un Pull Request (PR) en GitHub?

Un **Pull Request** (solicitud de extracción) es una propuesta para **fusionar cambios** desde una rama (branch) hacia otra dentro de un repositorio, normalmente hacia la rama principal (`main` o `master`).

Es una parte clave del flujo de trabajo colaborativo en Git, donde los cambios pueden ser revisados, discutidos y aprobados antes de integrarse al proyecto principal.

---

## 🔄 ¿Para qué se usa un Pull Request?

- Proponer nuevos cambios en el código.
- Solicitar revisión de código por parte del equipo.
- Discutir posibles mejoras o problemas antes de fusionar.
- Mantener un historial claro de contribuciones.

---

## 🧩 Estructura de un Pull Request

Un PR suele incluir:

- **Título** descriptivo del cambio.
- **Descripción** detallada de lo que se ha hecho y por qué.
- Comparación entre ramas: `rama-origen` → `rama-destino`.
- Posibilidad de **asignar revisores**, etiquetas o vincular issues relacionados.
- **Commits** realizados.
- **Archivos modificados**.
- Sección de **comentarios y revisión**.

---

## ✅ Ejemplo de Pull Request

```markdown
### Título: Agrega validación de formulario en la página de contacto

**Descripción:**
Este pull request agrega validaciones en el formulario de contacto para asegurarse de que los campos de nombre, correo y mensaje no estén vacíos.

**Cambios realizados:**
- Se añadió un archivo `validacion.js`.
- Se implementó la función `validarFormulario()`.
- Se actualizó `index.html` para vincular el nuevo script.

**Relacionado con:** Issue #42

**Etiquetas:** `enhancement`, `frontend`
