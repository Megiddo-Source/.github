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

subgraph CAD_LAYOUT
A[AutoCAD]
B[GLUKO Plugin]
C[Exportación tabla de layout]
end

subgraph CAD_MECANICO
D[Diseño máquina<br/>Solid Edge / CAD mecánico]
E[Extracción BOM]
end

subgraph DATOS_FABRICACION
F[CadXportData]
G[BOM / Materiales]
H[Pedidos BOM]
I[Documentación técnica<br/>PDF / DWG / DXF / STEP]
J[Procesos fabricación<br/>Laser / Corte / Plegado]
end

subgraph PLANIFICACION
K[FORGE]
L[Planificación Gantt]
M[Gestión de tareas]
end

subgraph PRODUCCION
N[Modo Taller]
O[Producción]
end

A --> B
B --> C

%% flujo diseño mecánico
C --> D
D --> E
E --> F

%% flujo proyecto cliente directo
C --> K

%% gestión datos técnicos
F --> G
F --> H
F --> I
F --> J

%% entrada planificación
G --> K
H --> K
J --> K

%% planificación
K --> L
K --> M

%% producción
M --> N
N --> O

style B fill:#16a34a,color:#fff
style F fill:#2563eb,color:#fff
style K fill:#ea580c,color:#fff
style O fill:#444,color:#fff
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
