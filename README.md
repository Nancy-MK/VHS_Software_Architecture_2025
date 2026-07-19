# Virtual Healthcare System (VHS) - Software Architecture

![UML](https://img.shields.io/badge/UML-diagrams-blue) ![Architecture](https://img.shields.io/badge/architecture-3--tier-green)

A software architecture design assignment for a **Virtual Healthcare System (VHS)**: a platform enabling remote patient-doctor interaction, appointment and prescription management, and administrative oversight.

## Overview

This project focuses on the architectural design phase of the software development lifecycle rather than implementation: translating a set of healthcare business requirements into a formal 3-tier architecture, a use-case model, and a class-level design ready for implementation.

## What's in this repository

- `assets/3_tier_diagram.png` - the presentation / business-logic / data layer architecture for the system
- `assets/Use case diagram.png` - actors (patients, doctors, administrators) and their interactions with the system
- `assets/class_diagram.png` - key entities, attributes, and relationships (patients, doctors, appointments, prescriptions, records)
- `assets/pdf_of_diagrams.pdf` - all diagrams collected in a single document
- `assets/202200396_Nancy.Mohamed_part1.pdf` - the full written submission, including design rationale and architectural justification

## Architectural approach

The system is structured as a classic **3-tier architecture**:

1. **Presentation tier** - the interfaces used by patients, doctors, and administrators to interact with the system
2. **Business logic tier** - appointment scheduling, prescription workflows, and access-control rules
3. **Data tier** - persistent storage for patient records, doctor profiles, and appointment history

Separating these tiers keeps the system maintainable and testable, and mirrors the layered reasoning used when assessing where risk and access-control controls should sit in a real healthcare system, an early example of the "map the system before you evaluate it" approach carried through my later AI governance and risk work.

## Skills demonstrated

- Requirements analysis and use-case modelling (UML)
- Class-level object-oriented design
- Layered / 3-tier software architecture
- Translating business requirements into implementable technical design

## Tech / notation

UML (Use Case, Class Diagrams), 3-tier software architecture

## Licence

Developed for academic purposes as part of the BSc Computer Science programme, University of Hertfordshire. All rights reserved (c) Nancy Kamal.
