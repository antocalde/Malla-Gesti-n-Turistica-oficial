# Malla Interactiva - Gestión Turística

Este repositorio contiene una visualización interactiva de la malla curricular de la carrera de Gestión Turística. Utiliza Mermaid.js para representar gráficamente los ramos por semestre y sus relaciones de prerrequisitos.

## 📊 Diagrama de Semestres 1 y 2

```mermaid
graph TD
  subgraph Semestre 1
    A1[Información y Orientación Turística]
    A2[Servicios Turísticos Guiados 🟢]
    A3[Ecosistemas Turísticos y Patrimonio 🟢]
    A4[Destinos Turísticos y Geografía 🧭]
    A5[Resolución de Problemas en Datos e Información]
    A6[Formación Ciudadana]
  end

  subgraph Semestre 2
    B1[Diseño de Programas Turísticos Globales 🧭]
    B2[Normativa y Prevención de Riesgos en Turismo 🚑]
    B3[Coordinación de Operaciones Turísticas 🟢]
    B4[Contabilidad de la Industria Turística 📊]
    B5[Administración 📊]
    B6[Inglés Inicial]
  end

  A4 --> B1
