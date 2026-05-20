# ES26UAB-451-02
Practicas ES-UAB
# QueMenges — Proyecto de Ingeniería del Software (UAB 2025–2026)

Bienvenido al repositorio del proyecto **QueMenges**, desarrollado en el marco de la asignatura **Enginyeria del Software** de la Universitat Autònoma de Barcelona.

El objetivo del proyecto es diseñar y especificar una aplicación que permita a usuarios acceder a menús preparados por cocineros particulares, gestionando perfiles, pedidos, envíos, pagos y valoraciones siguiendo la metodología **Scrum** y utilizando herramientas colaborativas.

---

## Equipo de desarrollo

| Nombre | Rol SCRUM |
|--------|-----------|
| Ty Devia Ballesteros | Scrum Master |
| Joan Gabriel Bestard Navarro | Scrum Team |
| Àlex Castillejo García | Scrum Team |

> **Tutor / Product Owner:** ES1

---

## Enlaces del proyecto

| Eina | URL |
|------|-----|
| Trello (Sprint Board) | https://trello.com/b/QbpWF5tW |
| Repositorio GitHub | https://github.com/tyGdev/ES26UAB-451-02 |

---

## Estructura del repositorio
---

## Sprint #1 — Definició de Requisits ✅

**Objectiu:** Captura i especificació dels requisits del sistema.

- Identificació de 48 requisits (34 funcionals + 14 no funcionals).
- Definició dels 4 perfils d'usuari: Client, Cuiner, Repartidor i Usuari no registrat.
- Creació de les primeres històries d'usuari (Backlog).
- Elaboració de la **versió 1.0 del Document d'Especificacions (SRS)**.
- Organització del Sprint a Trello (Backlog, tasques, seguiment).
- Generació de les primeres actes de reunió.

📄 Entregable: `documents/QueMenges_SRS_v1.0.pdf`

---

## Sprint #2 — Document SRS i Diagrames de Casos d'Ús ✅

**Objectiu:** Consolidació del SRS i elaboració dels diagrames de casos d'ús inicials.

- Revisió i actualització del Document d'Especificacions de Requisits (**SRS v1.1**).
- Elaboració del **Diagrama de Casos d'Ús general** del sistema (visió unificada dels 4 perfils).
- Elaboració dels diagrames de casos d'ús individuals per perfil:
  - Visió Client
  - Visió Cuiner
  - Visió Repartidor
  - Visió Usuari no registrat
- Especificació dels casos d'ús del perfil Cuiner (taules d'especificació).
- Actualització del Backlog i seguiment de tasques a Trello.

📄 Entregables:
- `documents/QueMenges_SRS_v1.1.pdf`
- `diagrams/CasosUs_General.pUML`
- `diagrams/CasosUs_Client.pUML`
- `diagrams/CasosUs_Cuiner.pUML`
- `diagrams/CasosUs_Repartidor.pUML`

---

## Sprint #3 — Especificacions i Diagrama de Classes ✅

**Objectiu:** Finalització dels casos d'ús i elaboració del diagrama de classes inicial.

- Finalització i revisió del **Diagrama de Casos d'Ús** (versió final).
- Elaboració de les **especificacions detallades** dels casos d'ús principals (taules d'especificació per perfil).
- Elaboració de la **versió inicial del Diagrama de Classes UML**:
  - Classes `«entity»`, `«control»` i `«boundary»`
  - Atributs, operacions i visibilitats
  - Relacions: associació, agregació, composició, herència i dependència
  - Multiplicitats i navegació
- Actualització del Backlog i seguiment de tasques a Trello.

📄 Entregables:
- `diagrams/CasosUs_Final.pUML`
- `diagrams/DiagramaClasses_v1.pUML`
- `documents/Especificacions_CasosUs_Cuiner.xlsx`

---

## Requisits

Els requisits es troben a la carpeta `/requirements/`, cadascun en un arxiu independent seguint la plantilla oficial:

- **Format:** `ID.md` (exemple: `RF-1-01.md`)
- **Contingut:** ID, tipus, versió, títol, descripció, relacions i comentaris.
- **Total:** 48 requisits (34 RF + 14 RNF)

---

## Actes de reunions

Totes les reunions de l'equip es documenten a `/minutes/` amb el format:

- **Format:** `meeting-YYYY-MM-DD.md`
- **Contingut:** data, assistents i decisions preses.

---

## Metodologia i eines

| Element | Detall |
|---------|--------|
| Metodologia | SCRUM (sprints setmanals) |
| Diagrames | UML amb PlantUML (`.pUML`) |
| Gestió de tasques | Trello (tauler per sprint) |
| Control de versions | GitHub |
| Documentació | Markdown + PDF |
| Burn-down charts | Excel / Google Spreadsheets |
