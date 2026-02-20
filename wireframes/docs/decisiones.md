# Decisiones de Diseño – Sistema Académico Accesible

## 1. Enfoque General del Proyecto

El sistema fue diseñado priorizando la accesibilidad como requisito no funcional principal. Desde la etapa de análisis se definió que el sistema debía cumplir con los criterios WCAG 2.2 nivel AA.

Esta decisión se relaciona con el área de Calidad del Software del SWEBOK, específicamente en usabilidad y requisitos no funcionales.

---

## 2. Diseño Centrado en el Usuario

Se definieron cuatro tipos de usuario con diferentes necesidades de accesibilidad:

- Estudiante con baja visión
- Profesor con limitaciones motrices
- Administrador con conexión lenta
- Estudiante con dislexia

Principio aplicado:
Ingeniería de Requisitos (SWEBOK) – Identificación de stakeholders y necesidades específicas.

---

## 3. Navegación por Teclado

Se implementó navegación tabular lógica en el prototipo para garantizar que el sistema pueda utilizarse sin mouse.

Relación con SWEBOK:
Diseño de Software – Diseño de interfaces accesibles.

Relación con WCAG:
Criterio 2.4.3 (Orden del foco) y 2.4.7 (Foco visible).

---

## 4. Uso de Alto Contraste

Los colores fueron seleccionados garantizando un contraste mínimo 4.5:1.

Relación con SWEBOK:
Calidad del Software – Atributo de accesibilidad.

Relación con WCAG:
1.4.3 Contraste mínimo.

---

## 5. Componentes Reutilizables en Figma

Se utilizaron componentes para mantener consistencia visual y facilitar mantenibilidad.

Relación con SWEBOK:
Diseño modular y reutilización.

---

## 6. Feedback del Sistema

Se diseñaron estados:
- Hover
- Focus
- Error
- Loading

Principio aplicado:
Heurística de Nielsen – Visibilidad del estado del sistema.

---

## 7. Estructura de Navegación

Se incorporaron:
- Breadcrumbs
- Skip links
- Landmarks ARIA

Relación con SWEBOK:
Arquitectura de Software – Organización estructural del sistema.
