# Evidencia del uso de IA

**Herramienta utilizada:** GitHub Copilot (Gemini 3.1 Pro Preview)

## Prompts Utilizados

1. **Planificación Scrum y Estructura:**
    * **Prompt del usuario:** "Quiero que actúes como un UX Engineer senior y Scrum Master. A continuación te pegaré un archivo en formato Markdown que contiene las instrucciones completas... Resume los objetivos... construye un plan de acción paso a paso para un solo estudiante... Asegúrate de que el plan de acción cubra todos los criterios de la rúbrica de evaluación sobre 2 puntos."
    * **Resultado:** Se generó el checklist paso a paso y la estructura de archivos `product_backlog.md` y `sprint_planning.md`.
2. **Restricción de BDD:**
    * **Prompt del usuario:** "Te tengo una nueva indicacion, NO DEBES TOCAR LA BDD, esta parte debe de permaner lo mas pura posible, y ademas te tengo una pregunta, estas tomando nota de todos los prompts que te estoy enviando?"
    * **Resultado:** Confirmación de no alterar backend/BDD y registro automático de la evidencia IA.
3. **Evaluación Heurística (Login y Dashboard):**
    * **Prompt del usuario:** "empecemos con la primera opcion si, ademas, note que a la pantalla de login le hace faltas cosas super basicas, como el poder recuperar...".
    * **Resultado:** Se integraron los problemas detectados en la imagen provista y se generaron los wireframes de la Fase 3.
    * Prompt:
    * Resultado: 

4. **Implementación Funcional y Configuración MCP:**
    * **Prompt del usuario:** "1. Configure MCP... Add to VS Code... 2. Install Agent Skills"
    * **Resultado:** Configuración del archivo `mcp.json` para Agent Skills de Supabase e inyección del código real de los Breadcrumbs (`<nav aria-label="Ruta de navegación">...</nav>`) en el `Layout.tsx`.

5. **Auditoría de Evidencia IA:**
    * **Prompt del usuario:** "Pregunta, solo para saber si estamos en la misma pagina, estas guardando TODA la evidencia, o estas saltandote informacion?"
    * **Resultado:** Re-verificación del documento `ai_evidence.md` garantizando que todo el historial conversacional clave exigido por la rúbrica (Scrum, Restricciones Técnicas, Heurísticas, Configuración y Auditoría) esté plasmado sin saltos.

## Impacto de la IA en el Diseño UX
El uso de herramientas de IA aceleró enormemente la detección de problemas heurísticos basados en el código fuente actual, evitando dependencias del backend. Redujo el tiempo de estructuración Scrum y tradujo requerimientos complejos en componentes funcionales de React/Tailwind integrables inmediatamente de forma precisa y contextual.
