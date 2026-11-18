# Resumen: Cómo usar Jira: una introducción (Guía de Atlassian)

## 1. ¿Qué es Jira?
Jira es una herramienta de gestión de proyectos para todos los equipos de una organización (como los de productos, marketing, etc.) que necesiten planificar, organizar y hacer un seguimiento de su trabajo mediante flujos de trabajo personalizables, tableros y capacidades de IA.

---

## 2. Conceptos Fundamentales

* **Espacio:** Lugar donde se almacena toda la actividad de un determinado equipo o proyecto, junto con su tablero, backlog y configuración que la respaldan.
* **Actividad (Actividades/incidencias):** Componentes básicos del espacio. Una actividad puede representar una historia, un epic, un error, una función o cualquier otra tarea a la que el equipo necesite hacer un seguimiento.
* **Actividades secundarias:** Subtareas más pequeñas en las que se puede dividir una actividad principal.
* **Tablero:** Interfaz que muestra las actividades distribuidas en columnas para representar el progreso del trabajo.
* **Columnas:** Cada columna del tablero representa una etapa en el flujo de trabajo del equipo a medida que la actividad avanza hacia su finalización.
* **Flujo de trabajo:** Proceso compuesto por estados, transiciones y reglas que sigue la actividad desde su inicio hasta completarse.

---

## 3. Tipos de Espacio

| Tipo de Espacio | Administración y Control | Caso de Uso |
|---|---|---|
| **Espacios gestionados por el equipo** | El propio equipo se encarga de su configuración y mantenimiento de forma simple e independiente. | Diseñados para equipos autónomos que quieren controlar sus propios procesos y prácticas de trabajo en un espacio independiente. |
| **Espacios gestionados por la empresa** | Los configuran y mantienen centralmente los administradores de Jira, compartiendo parámetros. | Diseñados para equipos que quieran estandarizar una misma forma de trabajar en muchos equipos (por ejemplo, compartiendo un mismo flujo de trabajo). |

---

## 4. Plantillas Mencionadas en la Guía

* **Scrum:** Se adapta a los equipos de metodología ágil que trabajan desde un backlog, planifican y estiman en sprints y entregan trabajo de forma periódica.
* **Kanban:** Ideal para cualquier equipo que gestione un flujo de trabajo continuo centrado en la actividad en curso, en lugar de trabajar en sprints.
* **Seguimiento de errores:** Funciona para equipos que prefieren gestionar las tareas de desarrollo y realizar el seguimiento de errores en una vista de lista en vez de en un tablero.

---

## 5. Pasos para la Configuración Inicial y Gestión

1. **Crea un espacio:** Iniciar sesión, seleccionar el icono "+" para crear un espacio en la barra lateral y explorar la biblioteca de plantillas por categoría o por aplicación.
2. **Selecciona una plantilla:** Elegir la plantilla (Scrum, Kanban, Seguimiento de errores u otra) y definir el tipo de espacio (gestionado por el equipo o gestionado por la empresa).
3. **Configura las columnas:** Añadir, renombrar, reordenar o eliminar columnas en el tablero según el tipo de espacio para reflejar el proceso de trabajo del equipo.
4. **Crea una actividad:** Seleccionar "+ Crear" en la barra de navegación global (o pulsar la tecla C). La nueva actividad aparecerá en el backlog o directamente en el tablero.
5. **Conecta tus herramientas:** Añadir aplicaciones e integraciones desde Atlassian Marketplace (como GitHub, Slack, Figma y Confluence) para que las actualizaciones aparezcan junto a las actividades.
6. **Invita a tu equipo:** Incorporar miembros al espacio para que puedan ver la actividad, tomar tareas y colaborar.
7. **Avanza el trabajo:** Crear e iniciar un sprint (en Scrum) o supervisar la actividad de inmediato arrastrando las actividades de una columna a la siguiente (en Kanban).

---

## 6. Funciones de Inteligencia Artificial (IA de Jira y Rovo)

* **División de actividades:** Redactar descripciones de actividades y dejar que la IA sugiera cómo dividir una actividad más grande en actividades secundarias más pequeñas.
* **Creador de flujos de trabajo:** Generar estados, transiciones y reglas automáticamente a partir de descripciones en lenguaje sencillo.
* **Agentes de IA (Rovo):** Asignar actividades directamente a agentes desde el campo de persona asignada, mencionarlos en comentarios para obtener resúmenes o borradores, o agregarlos a transiciones para que se ejecuten automáticamente según los permisos y el registro de auditoría.