# Culture Intelligence Platform

> An open-source Business Intelligence platform designed for museums and cultural institutions.

The **Culture Intelligence Platform** is a modular Business Intelligence ecosystem created to support cultural institutions in transforming collection data into strategic information.

The first module, **Museum Collections Observatory**, aims to consolidate information from Museums of Image and Sound (MIS) across Brazil, providing standardized indicators for institutional management, preservation planning and public communication.

---

# Vision

To become an open and reusable Business Intelligence platform capable of supporting museums, galleries, libraries, archives and other cultural institutions through standardized data collection, dimensional modeling, ETL processes and interactive dashboards.

---

# Philosophy

The platform follows one simple principle:

> **Maximum strategic value with minimum data collection effort.**

Instead of demanding perfect inventories, the platform accepts different levels of institutional maturity while maintaining transparency regarding data quality.

---

# Conceptual Framework

The Culture Intelligence Platform is built upon four conceptual pillars.

```
                          Culture Intelligence Platform

                                        │
      ┌───────────────────┬─────────────┼──────────────┬───────────────────┐
      │                   │             │              │
Representativeness   Materiality   Digital Accessibility   Data Maturity
      │                   │             │              │
 Collection Size      Supports      Digitization      Confidence
 Museum Network       Formats       Public Access     Completeness
 Geographic View      Preservation  Availability      Data Updates
```

---

## 🏛 Representativeness

Measures the scale and national relevance of cultural heritage preserved by participating institutions.

Examples

- Number of museums
- Total collection size
- Geographic distribution
- Growth over time

---

## 📦 Materiality

Describes how cultural heritage is physically preserved.

Examples

- Collection types
- Physical supports
- Preservation formats
- Storage characteristics

---

## 🌐 Digital Accessibility

Measures how accessible cultural heritage is through digital technologies.

Examples

- Digitization rate
- Public online access
- Digital preservation
- Access indicators

---

## 📈 Data Maturity

Measures the quality and reliability of institutional information.

Examples

- Complete inventories
- Partial inventories
- Estimated values
- Confidence level
- Last update

---

# Current Modules

| Module | Status |
|---------|--------|
| Museum Collections Observatory | 🚧 In Development |

Future modules

- Art Galleries Observatory
- Libraries Observatory
- Public Archives Observatory
- Cultural Heritage Observatory

---

# Project Architecture

```
                Google Forms
                       │
                       ▼
             Data Collection Layer
                       │
                       ▼
              Pentaho (ETL Process)
                       │
                       ▼
             Dimensional Data Model
                       │
                       ▼
              Power BI Service
                       │
                       ▼
             Interactive Dashboards
```

---

# Technology Stack

- Power BI
- Pentaho Data Integration (Kettle)
- Google Forms
- Google Sheets
- Git & GitHub

Future

- PostgreSQL
- Python
- Docker
- API Integrations

---

# Project Roadmap

## Phase 1

- [x] GitHub Repository
- [x] Project Documentation
- [x] Business Requirements
- [x] User Stories
- [x] Dimensional Modeling

## Phase 2

- [ ] Google Forms
- [ ] Data Collection
- [ ] Pentaho ETL
- [ ] Data Warehouse

## Phase 3

- [ ] Power BI Dashboard
- [ ] Power BI Service
- [ ] Public Demonstration

## Phase 4

- [ ] Gallery Module
- [ ] Libraries Module
- [ ] Archives Module

---

# Guiding Principles

- Open Source
- Reusable Architecture
- Data Transparency
- Incremental Documentation
- Modular Design
- Accessibility First
- Data Quality Awareness

---

# Repository Structure

```
culture-intelligence-platform/

├── data/
├── docs/
├── modules/
│   └── museum-collections-observatory/
├── LICENSE
├── README.md
└── .gitignore
```

---

# Contributing

This project is currently under active development.

Suggestions, discussions and collaborations are welcome.

---

# Author

**Luís Felipe Pinheiro**

Museologist | Data Analyst

LinkedIn

https://www.linkedin.com/in/luisfelipepinheiro/

---

# License

MIT License
