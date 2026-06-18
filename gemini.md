# 🎨 Design Pulse — Tendencias Semanales en Diseño

## Descripción del Proyecto

**Design Pulse** es una publicación web de formato editorial que presenta un resumen curado de las tendencias más relevantes en diseño, actualizado semanalmente. Está dirigida a estudiantes de nivel profesional en las carreras de Diseño de Producto, Diseño Industrial y Diseño de Experiencias (UX/UI).

El proyecto fue creado como herramienta didáctica para la clase de **Tendencias de Diseño**, permitiendo a los alumnos consultar en un solo lugar las tendencias actuales organizadas por disciplina.

---

## 🎯 Objetivos

### Objetivo General
Mantener a los estudiantes de diseño actualizados con las tendencias más relevantes de la industria, presentadas en un formato visual, accesible y profesional que sirva como referencia constante a lo largo del curso.

### Objetivos Específicos

1. **Informar** — Presentar las tendencias emergentes, en auge y consolidadas en tres disciplinas clave del diseño (Producto, Industrial y Experiencias).
2. **Contextualizar** — Explicar cada tendencia con su estado actual, descripción clara y palabras clave para que los estudiantes comprendan su relevancia.
3. **Conectar con la industria** — Destacar eventos, conferencias y noticias relevantes del mundo del diseño.
4. **Inspirar** — Utilizar un diseño editorial premium como referencia de buenas prácticas en diseño web y comunicación visual.
5. **Democratizar el acceso** — Publicar en GitHub Pages para que cualquier estudiante pueda acceder desde cualquier dispositivo sin necesidad de instalación.

---

## 📐 Estructura del Contenido

### Disciplinas cubiertas

| Disciplina | Enfoque semanal | Tendencias |
|---|---|---|
| **◆ Diseño de Producto** | Del experimento a la integración | UX Agéntica, Machine Experience (MX), Corrección Human-Led, Interfaces Adaptativas |
| **▲ Diseño Industrial** | Sostenibilidad inteligente | IA Generativa/Paramétrica, Economía Circular, Diseño Biofílico, Tecnología Invisible/IoT |
| **● Diseño de Experiencias** | Confianza, no espectáculo | Personalización Intent-Aware, Interfaces Espaciales, Accesibilidad Legal, Calm UI |

### Secciones adicionales
- **Insights transversales**: Datos clave que cruzan las tres disciplinas (MX, Circularidad 360°, Calm Design)
- **Eventos y noticias clave**: Conferencias, convocatorias y premios relevantes de la semana

---

## 🛠 Instrucciones Técnicas

### Tecnología utilizada
- **HTML5** semántico con CSS integrado (archivo único `index.html`)
- **Google Fonts**: Inter (sans-serif) + Playfair Display (serif)
- **Diseño**: Dark mode, glassmorphism, gradientes por disciplina, animaciones CSS
- **Responsive**: Adaptable a móvil, tablet y desktop
- **JavaScript**: Barra de progreso de lectura, navegación con scroll, animaciones de entrada

### Estructura de archivos
```
Tendencias-de-Dise-o/
├── index.html          # Archivo principal (toda la app)
├── images/             # (Pendiente) Imágenes hero por disciplina
│   ├── hero_product_design.jpg
│   ├── hero_industrial_design.jpg
│   └── hero_ux_design.jpg
└── gemini.md           # Este archivo de documentación
```

### Publicación con GitHub Pages
1. El repositorio está en: `github.com/nayra-me/Tendencias-de-Dise-o`
2. Activar GitHub Pages en **Settings → Pages → Branch: main / root**
3. La URL pública será: `https://nayra-me.github.io/Tendencias-de-Dise-o/`

### Actualización semanal
Para actualizar las tendencias cada semana:
1. Editar el contenido de las tarjetas de tendencia en `index.html`
2. Actualizar las fechas en el hero ("Edición Semanal") y el footer
3. Actualizar los eventos en la sección de "Eventos y noticias clave"
4. Hacer commit y push:
   ```bash
   git add .
   git commit -m "Actualización semanal: [fecha]"
   git push origin main
   ```

---

## 🎨 Sistema de Diseño

### Paleta de colores por disciplina
| Disciplina | Color primario | Gradiente |
|---|---|---|
| Diseño de Producto | Coral `#ff6b6b` + Amber `#ffa94d` | `135deg, coral → amber` |
| Diseño Industrial | Teal `#38d9a9` + Blue `#4dabf7` | `135deg, teal → blue` |
| Diseño de Experiencias | Violet `#9775fa` + Rose `#f06595` | `135deg, violet → rose` |

### Estados de tendencia
- 🔥 **En auge** — Tendencia en crecimiento rápido
- 🆕 **Emergente** — Recién apareciendo en la industria
- ⚡ **Consolidada** — Ya establecida como práctica estándar
- ↻ **Resurgencia** — Vuelve con fuerza después de un periodo de baja
- 🌿 **Creciendo** — Ganando tracción gradualmente
- 📋 **Mandato** — Requerida por regulación o legislación

---

## 👩‍🏫 Uso Didáctico

### Actividades sugeridas para clase
1. **Análisis crítico**: Los alumnos seleccionan una tendencia y debaten si aplica al contexto mexicano/local.
2. **Investigación complementaria**: Cada alumno profundiza en una tendencia y presenta hallazgos adicionales.
3. **Proyecto de diseño**: Aplicar una o más tendencias en un proyecto de diseño del semestre.
4. **Comparativa semanal**: Contrastar las tendencias de esta semana con la anterior para identificar evolución.
5. **Vocabulario profesional**: Usar las keywords de cada tendencia para construir un glosario del curso.

---

## 📝 Notas

- **Edición actual**: Semana 25 · 16–22 Junio 2026
- **Curación**: Contenido curado con IA + criterio humano
- **Imágenes**: Las imágenes hero por disciplina están referenciadas pero pendientes de agregar a la carpeta `images/`
- **Mantenimiento**: Se recomienda actualizar el contenido semanalmente para mantener la relevancia
