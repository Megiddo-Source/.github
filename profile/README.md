<div align="center">

# MEGIDDO SOURCE

<img
  width="1536"
  height="341"
  alt="Megiddo Source banner"
  src="https://github.com/user-attachments/assets/90acb32a-8cd8-450b-8013-e26cbd57ff66"
/>

### Software especializado para trabajar, crear y automatizar en local.

Megiddo Source desarrolla proyectos de software centrados en productividad,  
IA local, automatización, herramientas CAD y entornos industriales.

[Sitio web](https://megiddosource.netlify.app/)
·
[Proyectos](https://megiddosource.netlify.app/apps/)
·
[Nexus ERP Industrial](https://megiddosource.netlify.app/ecosystem.html)
·
[Distribución](https://megiddosource.netlify.app/downloads.html)

</div>

---

![Local software](https://img.shields.io/badge/software-local-111827)
![Local AI](https://img.shields.io/badge/AI-local-2563eb)
![Automation](https://img.shields.io/badge/focus-automation-d97706)
![Industrial tools](https://img.shields.io/badge/tools-industrial-166534)
![Megiddo Source](https://img.shields.io/badge/by-Megiddo%20Source-black)

## Sobre Megiddo Source

Megiddo Source es una iniciativa independiente de desarrollo de software.

Los proyectos se crean para resolver problemas concretos y pueden adoptar distintas formas:

- aplicaciones de escritorio;
- aplicaciones móviles;
- herramientas de IA local;
- extensiones de navegador;
- utilidades técnicas;
- proyectos industriales;
- prototipos e investigación.

La mayoría de los proyectos funcionan de manera independiente.

Actualmente, **Nexus ERP Industrial** es el único ecosistema formal en desarrollo dentro de Megiddo Source.

---

# Nexus ERP Industrial

Nexus ERP Industrial es una plataforma industrial en desarrollo para conectar progresivamente:

```text
CAD → Datos técnicos → Planificación → Producción
```

Está formada actualmente por tres proyectos principales:

## CadXportData

Automatización de BOM, documentación técnica, archivos CAD y datos de fabricación.

[![CadXportData](https://img.shields.io/badge/CadXportData-BOM%20%7C%20Manufacturing-2563eb?style=for-the-badge)](https://github.com/Megiddo-Source/CadXportData)

## Forge

Planificación de proyectos industriales, tareas, dependencias y seguimiento de producción.

[![Forge](https://img.shields.io/badge/Forge-Industrial%20Planning-ea580c?style=for-the-badge)](https://github.com/Megiddo-Source/Forge)

## GLUKO

Herramientas para AutoCAD orientadas a bloques, atributos, tablas y automatización de layouts industriales.

[![GLUKO](https://img.shields.io/badge/GLUKO-AutoCAD%20Automation-16a34a?style=for-the-badge)](https://github.com/Megiddo-Source/GLUKO)

> Los tres proyectos pueden funcionar de forma independiente mientras avanza la integración progresiva de Nexus ERP Industrial.

---

## Arquitectura prevista de Nexus ERP Industrial

```mermaid
flowchart LR

subgraph CAD_LAYOUT["Diseño de layout"]
    A[AutoCAD]
    B[GLUKO]
    C[Datos y tablas de layout]
end

subgraph CAD_MECANICO["Ingeniería mecánica"]
    D[Solid Edge / CAD mecánico]
    E[BOM y documentación]
end

subgraph DATOS["Datos de fabricación"]
    F[CadXportData]
    G[BOM y materiales]
    H[Pedidos]
    I[PDF / DWG / DXF / STEP]
    J[Procesos de fabricación]
end

subgraph PLANIFICACION["Planificación"]
    K[Forge]
    L[Planificación Gantt]
    M[Tareas y seguimiento]
end

subgraph OBJETIVO["Objetivo progresivo"]
    N[Nexus ERP Industrial]
    O[Producción y modo taller]
end

A --> B
B --> C

C --> D
D --> E
E --> F

F --> G
F --> H
F --> I
F --> J

G -. integración .-> K
H -. integración .-> K
J -. integración .-> K
C -. integración .-> K

K --> L
K --> M

M -. integración futura .-> N
N -.-> O

style B fill:#16a34a,color:#fff
style F fill:#2563eb,color:#fff
style K fill:#ea580c,color:#fff
style N fill:#7c5c24,color:#fff
```

### Leyenda

- Línea continua: flujo o capacidad actual.
- Línea discontinua: integración progresiva o prevista.
- Nexus ERP Industrial: objetivo de plataforma conjunta.

---

# Otros proyectos

Megiddo Source también desarrolla aplicaciones y herramientas independientes relacionadas con:

- IA local;
- productividad personal;
- desarrollo asistido;
- visualización CAD;
- automatización de navegador;
- doblaje y traducción local;
- generación multimedia;
- experiencias narrativas.

El catálogo público, el estado y la distribución de cada proyecto se mantienen en el sitio web:

[Explorar todos los proyectos](https://megiddosource.netlify.app/apps/)

No todos los proyectos disponen de repositorio público.

---

# Filosofía de desarrollo

Megiddo Source prioriza:

- software especializado frente a aplicaciones genéricas;
- procesamiento local cuando resulta viable;
- control del usuario sobre sus datos;
- automatización de trabajos repetitivos;
- aplicaciones independientes y modulares;
- integración únicamente cuando aporta un valor real;
- transparencia sobre el estado de desarrollo.

Compartir autor, tecnologías o filosofía no convierte automáticamente varios proyectos en un ecosistema.

---

# Estado de los proyectos

Los proyectos pueden encontrarse en diferentes etapas:

| Estado | Significado |
|---|---|
| Concepto | Dirección inicial definida |
| Investigación | Validación técnica o funcional |
| Prototipo | Implementación experimental |
| Preview | Funcionalidad utilizable todavía en evolución |
| Beta | Proyecto funcional en validación |
| Disponible | Publicación pública utilizable |
| Mantenimiento | Desarrollo centrado en estabilidad y correcciones |

Consulta la ficha de cada proyecto para conocer su estado real.

---

# Distribución

Megiddo Source no utiliza GitHub como única vía de distribución.

Según el proyecto, las publicaciones pueden encontrarse en:

- GitHub Releases;
- Gumroad;
- Chrome Web Store;
- Microsoft Edge Add-ons;
- Google Play;
- Autodesk App Store;
- otros distribuidores indicados en la web oficial.

[Consultar distribución oficial](https://megiddosource.netlify.app/downloads.html)

---

<div align="center">

<img
  width="100"
  height="100"
  alt="Megiddo Source watermark"
  src="https://github.com/user-attachments/assets/6f1bd1b5-5068-4a0c-a194-d409b2194700"
/>

**Megiddo Source**

Software especializado. Automatización práctica. Control local.

</div>
