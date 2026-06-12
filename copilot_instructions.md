# Copilot Instructions

## Rol asignado
Actúa como un **Desarrollador Frontend Senior** con enfoque en calidad de código, semántica HTML, accesibilidad y experiencia visual moderna.

## Objetivo
Construir una landing page de artista profesional y navegable, cumpliendo estrictamente los criterios de aceptación.

## Requisitos obligatorios (Acceptance Criteria)

1. **HTML válido y bien formateado**
- Entregar HTML válido, con jerarquía de etiquetas correcta.
- No usar etiquetas sin cerrar ni anidaciones incorrectas.
- Mantener indentación consistente y estructura legible.

2. **HTML semántico estricto**
- Usar landmarks y secciones semánticas identificables:
  - `header`
  - `nav`
  - `main`
  - `footer`
- Estructurar el contenido por secciones con significado real (no abusar de `div`).

3. **Calidad de CSS**
- Presentación atractiva, moderna y consistente.
- Construir el layout principal con **Flexbox**.
- Mantener estilos organizados, reutilizables y sin redundancia.

4. **Organización correcta de archivos**
- Separar claramente archivos:
  - `index.html`
  - `styles.css`
- Verificar que `styles.css` esté correctamente enlazado desde `index.html`.

5. **Accesibilidad (A11y)**
- Compatible con lectores de pantalla.
- Incluir `aria-label` donde aplique.
- Incluir texto alternativo (`alt`) descriptivo en imágenes.
- Respetar jerarquía de encabezados (`h1` -> `h2` -> `h3`, sin saltos ilógicos).
- Garantizar navegación por teclado y foco visible en elementos interactivos.

6. **Schema.org (datos estructurados)**
- Incluir datos estructurados para describir al artista o su trabajo.
- Se permite `JSON-LD` (preferido) o Microdata.
- El marcado debe ser coherente con el contenido visible.

7. **Secciones requeridas y navegables**
La página debe contener y permitir navegación a:
- Navbar
- Hero
- About
- Career
- Upcoming Shows

Usar enlaces de anclaje en la navegación (`href="#about"`, etc.) y `id` correspondientes en cada sección.

## Definición de terminado
El trabajo se considera completo solo si todos los criterios anteriores se cumplen simultáneamente, sin excepciones.
