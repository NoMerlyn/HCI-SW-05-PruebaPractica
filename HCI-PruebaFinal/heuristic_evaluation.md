# Evaluación Heurística

| ID | Pantalla | Descripción del Problema | Heurística Violada | Severidad |
|---|---|---|---|---|
| 1 | Login | El sistema no valida el formato del correo mientras se escribe; solo advierte al enviar el formulario (backend). | #5 Prevención de errores | Moderado |
| 2 | Login | El modal de "¡Revisa tu Email!" bloquea toda la pantalla y no puede cerrarse haciendo click fuera ni con la tecla ESC. | #3 Control y libertad del usuario | Leve |
| 3 | Login | Los labels de Email y Contraseña usan un tamaño de texto diminuto (10px) en mayúsculas y color gris claro, provocando baja legibilidad. | #4 Consistencia y estándares | Moderado |
| 4 | General / Navegación | Al navegar por proyectos y planes, no existen "Breadcrumbs" (Migas de pan). El usuario pierde fácilmente la ubicación actual. | #3 Control y libertad / #6 Reconocimiento | Crítico |
| 5 | Test Plan Form | La creación de una prueba involucra múltiples campos sin un "Stepper" (Indicador de Progreso), perdiendo noción de cuánto falta. | #1 Visibilidad del estado del sistema | Crítico |
| 6 | Dashboard | El botón y diálogo de "Eliminar Plan" no pide verificación tipográfica de seguridad (ej. "Escriba BORRAR"), lo que genera borrados accidentales irrecuperables. | #5 Prevención de errores | Crítico |
| 7 | Dashboard | La barra de búsqueda solo filtra por "Nombre del Producto"; si el usuario intenta buscar por método u otra variable, no funciona. | #7 Flexibilidad y eficiencia de uso | Moderado |
| 8 | Dashboard / Tablas | Al alternar entre planes "Ejecutados" y "Planificados", hay un recargo pesado de información sin jerarquía correcta para los KPIs clave. | #8 Diseño estético y minimalista | Moderado |
| 9 | Reportes / Dashboard | Los mensajes de éxito (como "Plan creado") aparecen y desaparecen a los 5 segundos sin permitir al usuario deshacer la acción (Undo). | #9 Ayudar a reconocer y recuperarse de fallos | Moderado |
| 10 | Login | Al enviar el formulario, aparece el loader de carga pero los inputs (email y password) no se deshabilitan, pudiendo ser editados. | #1 Visibilidad del estado del sistema | Leve |
