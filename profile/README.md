<div align="center">

# MEGIDDO SOURCE

<img
  width="1536"
  height="341"
  alt="Megiddo Source Banner"
  src="https://github.com/user-attachments/assets/90acb32a-8cd8-450b-8013-e26cbd57ff66"
/>

### Specialized software for productivity, local AI, automation, and industrial engineering.

Megiddo Source develops independent software projects focused on local-first computing,
technical productivity, automation, CAD workflows, and industrial solutions.

<div align="center">

[![Website](https://img.shields.io/badge/Website-Megiddo%20Source-gold?style=for-the-badge)](https://megidddosource.netlify.app)

[![Projects](https://img.shields.io/badge/Projects-Catalog-blue?style=for-the-badge)](https://megidddosource.netlify.app/apps/)

[![Nexus ERP](https://img.shields.io/badge/Nexus-ERP%20Industrial-orange?style=for-the-badge)](https://megidddosource.netlify.app/ecosystem.html)

[![Downloads](https://img.shields.io/badge/Downloads-Official-green?style=for-the-badge)](https://megidddosource.netlify.app/downloads.html)

</div>
</div>

---

![Local Software](https://img.shields.io/badge/Software-Local-111827)
![Local AI](https://img.shields.io/badge/AI-Local-2563eb)
![Automation](https://img.shields.io/badge/Focus-Automation-d97706)
![Industrial Tools](https://img.shields.io/badge/Tools-Industrial-166534)
![By Megiddo Source](https://img.shields.io/badge/by-Megiddo%20Source-black)

---

# About Megiddo Source

Megiddo Source is an independent software development initiative focused on building practical tools for professionals, creators, and local AI users.

Projects may include:

- Desktop applications
- Mobile applications
- Local AI tools
- Browser extensions
- CAD utilities
- Industrial software
- Automation tools
- Experimental research projects

Most applications are designed to work independently.

Currently, **Nexus ERP Industrial** is the primary ecosystem under active development inside Megiddo Source.

---

# Nexus ERP Industrial

Nexus ERP Industrial is a long-term industrial software platform designed to progressively connect engineering and manufacturing workflows.

Its objective is to integrate:

```text
CAD → Technical Data → Planning → Production
```

The ecosystem currently consists of three core applications.

---

## Forge

Industrial project planning with Gantt scheduling, task management, and production tracking.

[![Forge](https://img.shields.io/badge/FORGE-Industrial%20Planning-orange?style=for-the-badge)](https://github.com/Megiddo-Source/Forge)

---

## CadXportData

Technical data management for manufacturing, including BOM processing, engineering documentation, and production assets.

[![CadXportData](https://img.shields.io/badge/CADXPORTDATA-BOM%20%7C%20Manufacturing-blue?style=for-the-badge)](https://github.com/Megiddo-Source/CadXportData)

---

## GLUKO

AutoCAD productivity tools focused on layout engineering, block libraries, attribute automation, and technical table generation.

[![GLUKO](https://img.shields.io/badge/GLUKO-AutoCAD%20Automation-green?style=for-the-badge)](https://github.com/Megiddo-Source/GLUKO)

---

> These applications are fully usable as standalone products while progressively evolving toward the Nexus ERP Industrial ecosystem.

---

# Planned Nexus ERP Industrial Architecture

```mermaid
flowchart LR

subgraph CAD_LAYOUT["Layout Design"]
A[AutoCAD]
B[GLUKO]
C[Layout Tables]
end

subgraph CAD_MECHANICAL["Mechanical Design"]
D[Solid Edge / Mechanical CAD]
E[BOM Extraction]
end

subgraph TECHNICAL_DATA["Manufacturing Data"]
F[CadXportData]
G[Bill of Materials]
H[Purchase Orders]
I[Technical Documentation]
J[Manufacturing Processes]
end

subgraph PLANNING["Planning"]
K[Forge]
L[Gantt Planning]
M[Task Management]
end

subgraph PRODUCTION["Production"]
N[Nexus ERP Industrial]
O[Workshop Mode]
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

G -. Planned integration .-> K
H -. Planned integration .-> K
J -. Planned integration .-> K
C -. Planned integration .-> K

K --> L
K --> M

M -. Future integration .-> N
N -.-> O

style B fill:#16a34a,color:#fff
style F fill:#2563eb,color:#fff
style K fill:#ea580c,color:#fff
style N fill:#7c5c24,color:#fff
```

---

## Legend

- **Solid lines** represent implemented or currently available workflows.
- **Dashed lines** represent planned or progressive integrations.
- **Nexus ERP Industrial** represents the long-term integration goal.

---

# Other Projects

Besides Nexus ERP Industrial, Megiddo Source develops independent software in areas such as:

- Local Artificial Intelligence
- Desktop Productivity
- Development Tools
- CAD Viewers
- Browser Extensions
- Translation & Local Dubbing
- Multimedia Generation
- Storytelling Platforms
- Experimental Utilities

Not every project has a public repository.

The complete public catalog is available on the official website.

---

# Development Philosophy

Megiddo Source follows a few core principles:

- Local-first software whenever practical
- User control over data
- Automation of repetitive workflows
- Modular, standalone applications
- Integration only when it adds real value
- Clear project status and transparent development
- Practical tools over unnecessary complexity

Sharing the same author or technology does not automatically make separate projects part of the same ecosystem.

---

# Project Status

Projects may be found in different development stages:

| Status | Description |
|---------|-------------|
| Concept | Initial direction defined |
| Research | Technical validation |
| Prototype | Experimental implementation |
| Preview | Usable but evolving |
| Beta | Feature-complete with ongoing validation |
| Stable | Publicly available |
| Maintenance | Stability improvements and bug fixes |

Each project documents its own development status.

---

# Distribution

Depending on the project, releases may be available through:

- GitHub Releases
- Gumroad
- Chrome Web Store
- Microsoft Edge Add-ons
- Google Play
- Autodesk App Store
- Additional official distribution channels

---

<div align="center">

<img
width="100"
height="100"
alt="Megiddo Source"
src="https://github.com/user-attachments/assets/6f1bd1b5-5068-4a0c-a194-d409b2194700"
/>

**Megiddo Source**

*Specialized Software • Local AI • Industrial Automation*

</div>
