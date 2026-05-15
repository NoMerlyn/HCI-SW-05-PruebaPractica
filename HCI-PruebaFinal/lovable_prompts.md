# Prompts para lovable.dev

Estos son los prompts preparados para generar wireframes (Lo‑Fi / Mid‑Fi) en lovable.dev usando la aplicación desplegada como referencia.

---

## Prompt Principal — Dashboard (Breadcrumbs + Jerarquía)

Idioma: Español

Contexto: "Aplicación: Usability Test Dashboard 2.0 (URL: https://hci-sw-05.vercel.app). Queremos mejorar la navegación y la jerarquía visual del Dashboard. No modificar la lógica backend; solo proponer UI/UX y assets visuales." 

Instrucciones para el generador de wireframes:
- Página objetivo: Dashboard principal.
- Objetivos: Mostrar Breadcrumbs (Home / Organizaciones / Proyecto / Prueba), destacar botón primario 'Nueva Prueba', separar filtros (Buscar, Pestañas Ejecutados/Planificados) y mostrar cards de KPIs encima de la tabla de planes.
- Prioridad visual: Breadcrumbs arriba a la izquierda (pequeño, legible), título y subtítulo central, botón 'Nueva Prueba' a la derecha (CTA primaria), tarjetas KPI en una fila, tabla de planes con acciones a la derecha (Editar / Eliminar).
- Requerimientos accesibilidad: contraste suficiente, labels visibles, tamaños de texto legibles para desktop.
- Estilo: limpio, minimal (Tailwind-like): colores neutros, acento `#3b82f6` (azul primaria), bordes suaves y sombras sutiles.
- Entregables: exportar Lo‑Fi y Mid‑Fi (PNG o SVG) y un breve texto con la jerarquía visual (qué componentes se priorizan).

Prompt concreto (copiar a lovable.dev):
"Genera wireframes Lo‑Fi y Mid‑Fi para el Dashboard de 'Usability Test Dashboard 2.0' (https://hci-sw-05.vercel.app). Incluir: 1) Breadcrumbs: Home / Organizations / Project / TestPlan; 2) Header con título y CTA 'Nueva Prueba'; 3) Filtro de búsqueda y pestañas 'Ejecutados | Planificados'; 4) Fila de KPIs; 5) Tabla de planes con acciones 'Editar' y 'Eliminar'. Usa estilo limpio, acento azul #3b82f6, alto contraste, y exporta imágenes PNG y una breve descripción textual de la jerarquía visual."

---

## Prompt Secundario — Login (mejoras de accesibilidad y recuperación de contraseña)

Contexto: Mejorar micro-interacciones del Login sin tocar backend; incluir show/hide password y modal UI para recuperación.

Prompt:
"Diseña un wireframe Mid‑Fi para la pantalla de Login del 'Usability Test Dashboard 2.0' (https://hci-sw-05.vercel.app). Elementos: logo, email, password con toggle show/hide, botón principal 'Iniciar sesión', enlace '¿Olvidaste tu contraseña?' que abre un modal UI-only (sin llamadas), mensajes de error visibles y foco accesible. Estilo: coherente con el Dashboard, botones grandes y legibles. Exportar PNG y lista de estados UI (idle, loading, error, success modal)."

---

## Prompt Auxiliar — Formulario de Test Plan (Stepper UI)

Contexto: Formulario multipaso para crear planes de prueba; queremos una barra de progreso/stepper.

Prompt:
"Genera un wireframe Mid‑Fi para un formulario de creación de 'Test Plan' con Stepper visual de 4 pasos: 1) Contexto, 2) Tareas, 3) Roles, 4) Notas. Incluir botones 'Atrás' y 'Siguiente', botón 'Guardar progreso' y mensajes de validación in‑line. Exportar imágenes y breve descripción del comportamiento del Stepper (estado activo, completado, bloqueado)."

---

Notas de uso:
- URL de referencia: https://hci-sw-05.vercel.app (usar para inspección visual si la plataforma lo permite).
- Reutilizar paleta y token `#3b82f6` para consistencia.
- Estos prompts se pueden adaptar a variaciones: (i) enfoque móvil, (ii) alta densidad de datos, (iii) modo oscuro.

---

Si querés, puedo: (A) ejecutar cargas a lovable.dev (necesitaría tus credenciales/permiso), o (B) generar un ZIP con los prompts y guidelines para compartir. ¿Cuál preferís?
