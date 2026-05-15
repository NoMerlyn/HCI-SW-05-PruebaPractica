# Wireframes: Rediseño Dashboard (Migas de Pan y Jerarquía)

## Lo-Fi / Mid-Fi Concept (Arquitectura de Información)

A continuación se muestra el esquema conceptual de cómo mejoraremos el `DashboardPage.tsx` integrando los **Breadcrumbs** (Migas de Pan) en la parte superior para solucionar el problema heurístico crítico de navegación.

```mermaid
graph TD
    classDef layout fill:#f8fafc,stroke:#94a3b8,stroke-width:2px;
    classDef nav fill:#e2e8f0,stroke:#64748b,stroke-width:1px;
    classDef card fill:#fff,stroke:#cbd5e1,stroke-width:1px,border-radius:8px;
    classDef primary fill:#3b82f6,stroke:#1d4ed8,color:#fff;

    A[Sidebar Navigation]:::layout --> B[Dashboard Main Content & Layout]:::layout
    B --> C[🟢 BREADCRUMBS NUEVAMENTE INGRESADOS 🟢<br> Home / Proyectos / Detalles]:::nav
    B --> D[Header: Título y Botón 'Nueva Prueba']:::card
    B --> E[Filtros y Pestañas: Ejecutados | Planificados]:::nav
    B --> F[Cards de KPIs<br>Observaciones | Findings | Tasa ...]:::card
    B --> G[Tabla de Planes de Prueba]:::card
```

### Elementos UX a Implementar:
1. **Breadcrumbs (`<Layout />` o `<DashboardPage />`)**: Un enlace de navegación contextual de la forma: `Dashboard > Proyecto X > Plan de Prueba Y`. Esto ayuda a cumplir la heurística #3 (Control y libertad del usuario) y #6 (Reconocer en lugar de recordar).
2. **Jerarquía Visual Mejorada**: Separación clara entre el filtro de búsqueda y las pestañas visuales de estado.

*Nota:* Para la entrega real, asegúrate de realizar un par de capturas o un archivo en Figma rápido, pero con este concepto cubrimos la documentación de la Fase 3.
