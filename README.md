# Ruta Nube e IA

Ingeniero electronico con mas de 20 anos en operaciones de red, testing y soporte Azure,
documentando mi transicion hacia ingenieria de nube, automatizacion e IA.

Plan de capacitacion en 5 practicas para cerrar brechas tecnicas en Python, Linux, Git, REST, SQL,
Docker, CI/CD, Terraform, IA en Azure y VXLAN/EVPN. Cada practica deja un proyecto en su carpeta.

Regla: el curso es la guia, el proyecto es la prueba.

Inicio: octubre 2026.

## About (English)

Electronics engineer with 20+ years in network operations, testing and Azure support, documenting
my transition into cloud engineering, automation and AI. This repository holds 5 hands-on projects:
a Python network tool, CI/CD with containers, Terraform on Azure, an AI agent on Azure AI Foundry,
and a VXLAN/EVPN data center fabric.

## Avance

- [ ] [Fase 0 - Preparar el entorno](fase-0-entorno/)
- [ ] [Practica 1 - Herramienta de red en Python](practica-1-netcheck/)
- [ ] [Practica 2 - CI/CD con contenedores](practica-2-cicd/)
- [ ] [Practica 3 - Infraestructura como codigo](practica-3-terraform/)
- [ ] [Practica 4 - IA operada](practica-4-ia/)
- [ ] [Practica 5 - Fabric de data center](practica-5-vxlan/)
- [ ] [Refuerzo - SQL y monitoreo](refuerzo-sql-monitoreo/)
- [ ] Certificacion AI-102
- [ ] Certificacion SC-500

```mermaid
flowchart TD
  S0["<b>Fase 0 - Preparar el entorno</b><br/>WSL Ubuntu - VS Code - Git - cuenta GitHub<br/>2 dias"]
  P1["<b>Practica 1 - Herramienta de red en Python</b><br/>Python - Linux - Git - REST - JSON - SQL<br/>Semanas 1-3"]
  P2["<b>Practica 2 - CI/CD con contenedores</b><br/>Docker - pytest - GitHub Actions<br/>Semana 4"]
  P3["<b>Practica 3 - Infraestructura como codigo</b><br/>Terraform - hub-spoke - Private Endpoint - DNS<br/>Semana 5 - Azure pago por uso con presupuesto"]
  P4["<b>Practica 4 - IA operada</b><br/>Foundry - Azure OpenAI - AI Search - App Insights<br/>Semana 6"]
  P5["<b>Practica 5 - Fabric de data center</b><br/>Spine-leaf - VXLAN - EVPN - API REST AOS-CX<br/>Semana 7"]
  C["<b>Despues del plan</b><br/>Certificacion AI-102 y luego SC-500"]
  ENT{{"Entrevista con brechas de SQL o monitoreo?"}}
  R["<b>Refuerzo - SQL y monitoreo</b><br/>SQL intermedio - KQL - Application Insights<br/>1-2 semanas - mediano plazo"]
  S0 --> P1 --> P2 --> P3 --> P4 --> C
  P1 -. reutiliza Python y REST .-> P5
  P5 --> C
  ENT -. adelantar .-> R
  R -. adelanta SQL .-> P1
  R -. adelanta observabilidad .-> P4
  subgraph PAR["Hilos paralelos durante todo el plan"]
    IA["<b>Hilo IA ligero</b> - 30 a 45 min por dia<br/>AI Fluency, Claude 101, MCP, Subagents"]
    EMP["<b>Hilo empleabilidad</b><br/>CV y LinkedIn al cerrar cada practica<br/>STAR de liderazgo - seguir aplicando"]
  end
  classDef s0 fill:#eef0ee,stroke:#7a8580,stroke-width:2px,color:#1d2420
  classDef p1 fill:#e4effa,stroke:#1f6fb2,stroke-width:2px,color:#1d2420
  classDef p2 fill:#fbefe1,stroke:#c2711b,stroke-width:2px,color:#1d2420
  classDef p3 fill:#efeafa,stroke:#6a4fb0,stroke-width:2px,color:#1d2420
  classDef p4 fill:#e2f4ee,stroke:#0f8a6c,stroke-width:2px,color:#1d2420
  classDef p5 fill:#f9e6e9,stroke:#b23b4a,stroke-width:2px,color:#1d2420
  classDef gate fill:#fff8e1,stroke:#b98a1e,stroke-width:2px,color:#1d2420
  classDef ref fill:#e3f3f8,stroke:#1e88a8,stroke-width:2px,color:#1d2420
  classDef par fill:#ffffff,stroke:#7a8580,stroke-dasharray:4 3,color:#1d2420
  class S0 s0
  class P1 p1
  class P2 p2
  class P3 p3
  class P4 p4
  class P5 p5
  class ENT gate
  class R ref
  class C,IA,EMP par
```

## Carpetas

| Carpeta | Contenido | Semanas |
|---|---|---|
| [`fase-0-entorno`](fase-0-entorno/) | WSL, VS Code, Git, GitHub | 2 dias |
| [`practica-1-netcheck`](practica-1-netcheck/) | Herramienta de red en Python: REST, JSON, SQLite, reporte | 1-3 |
| [`practica-2-cicd`](practica-2-cicd/) | Docker, pruebas con pytest, GitHub Actions | 4 |
| [`practica-3-terraform`](practica-3-terraform/) | Terraform en Azure: hub-spoke, Private Endpoint, Private DNS | 5 |
| [`practica-4-ia`](practica-4-ia/) | Agente en Foundry con RAG y monitoreo en App Insights | 6 |
| [`practica-5-vxlan`](practica-5-vxlan/) | Spine-leaf con VXLAN/EVPN en AOS-CX y automatizacion REST | 7 |
| [`refuerzo-sql-monitoreo`](refuerzo-sql-monitoreo/) | SQL intermedio, KQL y Application Insights | 1-2, mediano plazo |

## Reglas del repositorio

- Nombres de archivos y carpetas en minusculas, con guiones, sin espacios, sin tildes y sin enes.
- Nunca subir claves, contrasenas ni archivos `.env` con secretos.
- Usar `.gitignore` para excluir `.env`, `venv/` y `__pycache__/`.

## Contacto

- LinkedIn: [Jose Luis Ardila](https://www.linkedin.com/in/joseluisardila)
- GitHub: [jlrdlab](https://github.com/jlrdlab)
