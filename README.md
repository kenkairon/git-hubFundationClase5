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


### Título: Agrega validación de formulario en la página de contacto

**Descripción:**
Este pull request agrega validaciones en el formulario de contacto para asegurarse de que los campos de nombre, correo y mensaje no estén vacíos.

**Cambios realizados:**
- Se añadió un archivo `validacion.js`.
- Se implementó la función `validarFormulario()`.
- Se actualizó `index.html` para vincular el nuevo script.

**Relacionado con:** Issue #42

**Etiquetas:** `enhancement`, `frontend`

# 🔗 Cómo asociar Pull Requests con Issues en GitHub

Vincular un **Pull Request (PR)** con un **Issue** permite mantener el seguimiento del trabajo y automatizar el cierre de issues cuando se fusiona el PR.

---

## 🧠 ¿Por qué asociarlos?

- Facilita la **trazabilidad** del trabajo realizado.
- Permite **cerrar automáticamente un issue** cuando se aprueba y fusiona un PR.
- Mejora la organización y la **colaboración en equipo**.

---

## ✅ Formas de asociar un PR con un Issue

### 1. Cierre automático (más usada)

En la descripción del Pull Request, usa **palabras clave** seguidas del número del issue:


Fixes #123
Closes #45
Resolves #78

Fixes #12, closes #15, resolves #20
Related to #123
References #45
See also: #67

### Título: Mejora la validación de formularios

**Descripción:**
Este PR mejora la validación del formulario para evitar envíos vacíos y asegura que el email tenga el formato correcto.

Fixes #42
Related to #40

**Cambios realizados:**
- Añade expresiones regulares para validar email.
- Muestra mensajes de error debajo de los campos.

**Revisores:** @usuario1 @usuario2
