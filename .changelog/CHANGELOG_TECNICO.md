# 📋 Registro Técnico de Cambios

> Documento generado automáticamente con cada commit realizado en el proyecto.
> Contiene el detalle técnico completo de cada cambio para el equipo de desarrollo.

---

## feat: Rediseño visual del perfil, integración de nueva marca y destaque de proyectos insignia

| Campo | Detalle |
|-------|---------|
| **Fecha** | 2026-07-21 19:18:00 |
| **Autor** | David Mendez (demg@outlook.com) |
| **Branch** | main |
| **Tipo** | Feature / Documentation |

### Archivos Modificados

| Archivo | Estado | Descripción del Cambio |
|---------|--------|----------------------|
| `README.md` | Modificado | Rediseño integral de presentación, hero banner, showcase de proyectos insignia y badges |
| `assets/Logo.jpeg` | Agregado | Nuevo logo oficial de la marca DEMG-DEV |
| `.gitignore` | Agregado | Exclusión de archivos del sistema operativo (`.DS_Store`) |

### Detalle Técnico

- **Identidad de Marca & Hero Section**: Se sustituyeron los assets antiguos por `assets/Logo.jpeg` estilizado en contenedor centrado con sombra de elevación, esquinas redondeadas (`border-radius: 20px`) y badges alineados.
- **Showcase de Proyectos Insignia (Featured Projects)**:
  - **GT7 Telemetry Pro (`RGDev.App.GT7TelemetryPro`)**: Inclusión de panel de dos columnas con badges técnicos (Python 3.10+, PyQt6, SQLite WAL), descripción del motor de telemetría a 60 FPS, instrumentación `QPainter`, 4 gráficas apiladas MoTeC i2 y heurística de circuitos.
  - **AC Results Analyzer (`RGDev.App.AssettoCorsaResultsAnalizer`)**: Presentación con badges (React 19, TypeScript 5.x, Vercel Blob), resumen de 7 gráficas motorsport F1 style, temas de escuderías y resolución de datos.
- **Compatibilidad con Markdown Previewers**: Optimización del contenedor de imágenes de estadísticas de GitHub a etiquetas `<p align="center">` limpias para evitar restricciones de Content Security Policy (CSP) en vistas previas locales de IDEs.
- **High-Availability Mirror**: Actualización del endpoint de `github-readme-stats` apuntando a un mirror activo (`github-readme-stats-sigma-five.vercel.app`) debido al estado pausado del dominio principal.
- **Configuración Git**: Creación del archivo `.gitignore` para ignorar `.DS_Store`.

### Fragmentos de Código Relevantes

```diff
+<p align="center">
+  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=DEMG-DEV&show_icons=true&count_private=true&theme=vision-friendly-dark&include_all_commits=true&hide_border=true" alt="Estadísticas de GitHub" height="165" />
+  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=DEMG-DEV&layout=compact&theme=vision-friendly-dark&hide_border=true" alt="Lenguajes Más Usados" height="165" />
+</p>
```

---
