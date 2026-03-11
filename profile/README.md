# Megiddo Source
<img width="1536" height="341" alt="Megido_source_banner" src="https://github.com/user-attachments/assets/90acb32a-8cd8-450b-8013-e26cbd57ff66" />


![platform](https://img.shields.io/badge/platform-Windows-lightgrey)
![cad](https://img.shields.io/badge/CAD-AutoCAD-blue)
![workflow](https://img.shields.io/badge/workflow-Industrial%20Engineering-darkgreen)
![brand](https://img.shields.io/badge/by-Megiddo%20Source-black)

---
[![Forge](https://img.shields.io/badge/FORGE-Industrial%20Planning-orange?style=for-the-badge)](https://github.com/Megiddo-Source/Forge)
[![CadXportData](https://img.shields.io/badge/CADXPORTDATA-BOM%20%7C%20Manufacturing-blue?style=for-the-badge)](https://github.com/Megiddo-Source/CadXportData)
[![GLUKO](https://img.shields.io/badge/GLUKO-AutoCAD%20Layout-green?style=for-the-badge)](https://github.com/Megiddo-Source/GLUKO)


Industrial engineering software ecosystem.

Megiddo Source desarrolla herramientas para automatizar el flujo técnico entre **CAD, planificación, producción y documentación industrial**.


---

```markdown
## Suite de software

### FORGE
Planificación industrial basada en tareas, dependencias y gestión de proyectos de fabricación.

### CADXPORTDATA
Gestión de BOM, documentación técnica (PDF / DWG / DXF / STEP) y coordinación entre ingeniería y producción.

### GLUKO
Plugin para AutoCAD orientado a ingeniería de layout industrial y generación automática de tablas técnicas.
```
---
## Aplicaciones


### FORGE
Planificación industrial basada en tareas y dependencias.

[![Forge](https://img.shields.io/badge/FORGE-Industrial%20Planning-orange?style=for-the-badge)](https://github.com/Megiddo-Source/Forge)

---


### CADXPORTDATA
Gestión de datos técnicos, BOM y documentación de fabricación.

[![CadXportData](https://img.shields.io/badge/CADXPORTDATA-BOM%20%7C%20Manufacturing-blue?style=for-the-badge)](https://github.com/Megiddo-Source/CadXportData)

---

### GLUKO
Plugin para AutoCAD orientado a layout industrial.

[![GLUKO](https://img.shields.io/badge/GLUKO-AutoCAD%20Layout-green?style=for-the-badge)](https://github.com/Megiddo-Source/GLUKO)


---

# Arquitectura del sistema

```mermaid
flowchart LR

subgraph CAD
A[AutoCAD]
B[GLUKO Plugin]
end

subgraph Datos
C[CadXportData]
D[BOM / Materiales]
E[Documentación PDF / DWG / DXF]
end

subgraph Planificacion
F[FORGE]
G[Planificación Gantt]
H[Gestión de tareas]
end

subgraph Produccion
I[Modo Taller]
J[Producción]
end

A --> B
B --> C
C --> D
C --> E
D --> F
F --> G
F --> H
H --> I
I --> J

style B fill:#16a34a,color:#fff
style C fill:#2563eb,color:#fff
style F fill:#ea580c,color:#fff
style J fill:#444,color:#fff
```

---

# Filosofía

Reducir trabajo manual en ingeniería industrial mediante herramientas que conectan:

```
CAD → Datos → Planificación → Producción
```

---

# Estado

Proyecto en desarrollo activo.
---

<img width="100" height="100" alt="megiddo_watermark" src="https://github.com/user-attachments/assets/6f1bd1b5-5068-4a0c-a194-d409b2194700" />

---
