# Sistema de Gestión y Administración Escolar - Capstone 2025

## Introducción

Bienvenidos a la organización oficial del proyecto **Sistema de Gestión y Administración Escolar**. Este espacio ha sido creado para centralizar, documentar y mostrar los avances del proyecto Capstone 2025 de la carrera de Ingeniería en Informática.

El objetivo de este proyecto es desarrollar una plataforma web integral que optimice los procesos académicos y administrativos de una institución educativa, facilitando la gestión de información para profesores, administrativos y estudiantes.

---

## 👨‍💻 Integrantes del Equipo

-   **Aaron Fuentes**
-   **Gaspar Lema**
-   **Cristian Gaete**

---

## 📝 Descripción del Proyecto

El **Sistema de Gestión y Administración Escolar** es una aplicación web robusta y escalable diseñada para modernizar la gestión educativa. La plataforma ofrece dashboards personalizados y herramientas específicas para los distintos roles dentro de la comunidad escolar, asegurando un acceso rápido y seguro a la información relevante.

### ✨ Características Principales

El sistema se estructura en torno a los siguientes módulos clave:

#### 🔐 Sistema de Autenticación Seguro

Implementamos un mecanismo de autenticación basado en **JSON Web Tokens (JWT)** para garantizar la seguridad y la correcta segmentación de acceso.
-   **Autenticación de usuarios:** Validación de credenciales (usuario y contraseña).
-   **Generación de tokens JWT:** Creación de tokens que contienen información del usuario y su rol.
-   **Protección de rutas:** Middleware que verifica la validez del token en cada solicitud a rutas protegidas.
-   **Redirección basada en roles:** Direccionamiento automático a dashboards específicos (profesor, alumno, administrativo) tras un inicio de sesión exitoso.

---

## 🧑‍🏫 Dashboard del Profesor

Interfaz centralizada diseñada para que los docentes gestionen eficientemente sus cursos y estudiantes.

### 📊 Vista Principal del Dashboard
-   **Selección de cursos:** Listado de los cursos impartidos en el período actual.
-   **Métricas por curso:** Visualización rápida de asistencia promedio, promedio de notas y distribución de calificaciones por rangos.
-   **Horario del día:** Agenda cronológica de las clases programadas para la jornada.

### ✅ Módulo de Toma de Asistencia
-   **Detección automática de la clase:** El sistema sugiere la clase correspondiente según la hora actual.
-   **Listado de estudiantes:** Interfaz intuitiva para marcar el estado de asistencia (presente, ausente, tarde).
-   **Búsqueda y estadísticas en tiempo real:** Filtro de estudiantes y conteo actualizado de la asistencia.

### 🗓️ Gestión de Horarios
-   **Resumen estadístico:** Total de horas lectivas, cursos activos y aulas utilizadas.
-   **Vista de calendario semanal:** Representación gráfica e interactiva del horario del profesor.
-   **Vista de lista detallada:** Alternativa tabular para una visualización clara del horario.

### 💯 Gestión de Evaluaciones y Calificaciones
-   **Métricas avanzadas por curso:** Promedio general, notas extremas y tasa de aprobación.
-   **Administración de evaluaciones:** Creación, edición y eliminación de pruebas, trabajos y proyectos.
-   **Ingreso de calificaciones:** Vista por evaluación o por estudiante para facilitar el ingreso de notas.

### 📋 Sistema de Observaciones
-   **Registro detallado:** Formulario para añadir observaciones (positivas, negativas, informativas) a los estudiantes, con posibilidad de adjuntar archivos.
-   **Filtros y estadísticas:** Búsqueda avanzada de observaciones y visualización de tendencias.

### 👨‍🎓 Gestión de Estudiantes
-   **Perfil completo del estudiante:** Acceso a información personal, historial de calificaciones, registro de asistencia y observaciones.
-   **Métricas clave del curso:** Identificación de estudiantes con riesgo académico y necesidades especiales.
-   **Gráficos de evolución académica:** Seguimiento visual del progreso de cada alumno.

---

## 🏢 Dashboard Administrativo

Panel de control global para la gestión y supervisión de toda la institución.

### 📈 Panel de Resumen Institucional
-   **Métricas clave en tiempo real:** Total de estudiantes, profesores, promedio académico general y asistencia histórica.
-   **Gráficos de rendimiento:** Visualización de la distribución del rendimiento académico y tendencias de asistencia semanal.

### 👥 Gestión de Usuarios
-   **Directorio completo:** Listado de todos los miembros de la comunidad educativa (alumnos, profesores, administrativos).
-   **Búsqueda y filtros avanzados:** Herramientas para encontrar y gestionar usuarios de manera eficiente.

### 📄 Módulo de Reportes
-   **Generación de reportes institucionales:** Creación de informes personalizables de asistencia, calificaciones y observaciones.
-   **Exportación en múltiples formatos:** Disponibilidad para descargar los reportes en PDF y Excel.

### 🔬 Análisis y Métricas Institucionales
-   **Indicadores académicos clave:** Medición de la tasa de aprobación, retención estudiantil y evolución del promedio institucional.
-   **Análisis gráfico avanzado:** Comparativas de rendimiento por materia, tendencias de asistencia y estadísticas disciplinarias.

---

## 🚀 Próximos Pasos y Funcionalidades por Definir

El proyecto se encuentra en desarrollo activo. Las siguientes áreas y funcionalidades están pendientes de definición y serán abordadas en futuras etapas, tras la validación con los stakeholders ("clientes"):

-   [ ] Módulo de comunicación interna (mensajería).
-   [ ] Dashboard del estudiante y apoderado.
-   [ ] Integración con sistemas de calendario externos.
-   [ ] Módulo de gestión de recursos (aulas, equipamiento).
-   [ ] Personalización de los criterios de evaluación.

> Agradecemos su interés y seguimiento a nuestro proyecto. Para cualquier consulta, no dude en contactar a los miembros del equipo.
